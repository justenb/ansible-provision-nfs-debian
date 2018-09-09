# ansible nfs client/server install  ( debian based distros )                                                                                                                      


## Installation                                                                                                                                                            

### Requirements                                                                                                                                                           
* ansible >= 2.4                                                                                                                                                           


## Usage    
clone the repository, eg.                                                                                                                                                               
```
git clone https://github.com/justenb/ansible-provision-nfs-debian
```
playbook example
```
cd ansible-provision-nfs-debian
ansible-playbook -i hosts playbook-example.yml -b -K
```
inventory example                                                                                                                                         

```ini                                                                                                                                                                     
[nfs-server]                                                                                                                                                               
server1 ansible_ssh_host=                                                                                                                                                  

[nfs-clients]                                                                                                                                                              
client1 ansible_ssh_host=                                                                                                                                                  
client2 ansible_ssh_host=                                                                                                                                                  
```                                                                                                                                                                        

## License                                                                                                                                                                 
[MIT](https://choosealicense.com/licenses/mit/)   
