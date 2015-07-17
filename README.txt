This repository can be used to add config to routers which are running junos os.
You need to run "python config.py" and then run "ansible-playbook junos.yml" to add the new config to your router.
You can see all of the set commands that you will run on your router in the test.set file. First check test.set and make sure if everything is correct and does not have any conflict with your previous configuration. Then you can run ansible commands. 
