# App Testing with Vagrant and VirtualBox

### Prerequisites:
- Install Vagrant.
- Install VirtualBox.

### To run
- From inside the folder, run 'vagrant up'.
- SSH into the virtual machine using 'vagrant ssh'.
- Move to the app folder using 'cd /app'
- Run 'npm install'
- Run 'npm start &'
- Open your browser and go to development.local:3000. You should see the front page.
- To run the tests, exit the VM using 'exit' and then enter 'cd environment/spec-tests'/
- Then run rake spec. All tests should pass.
