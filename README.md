# switch_proxy_on_bashrc

Please save as a ".bashrc"　and use it if your work or school has a proxy set up.

## Description
First, configure the network environment.

--Mac--

System Preference → Network →　Edit network environment → Name it appropriately(I named "University")
→ Set proxy → Apply
 
--Windows--

 I don't know.
  
After that save "bashrc.txt" as a ".bashrc" and write a your proxy server name on "proxyserver" in 
1 proxy="http://proxyserver:8080"

Finally, Write a "source ~/.bashrc" on "bash_profile".

if you don't make ".bash_profile" on home directory, please execute "touch .bash_profile"

Completed by restarting the terminal.

## Demo

