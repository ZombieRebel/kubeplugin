Step 1

# "install" your plugin by moving it to a directory in your $PATH
sudo mv ./kubectl-kubeplugin /usr/local/bin

Step 2

# check that kubectl recognizes your plugin
kubectl plugin list

Step 3

#run plugin with a command

kubectl kubeplugin {NAMESPACE} {RESOURCE_TYPE}