# ansible-playbooks

## minikube openstack
`openstack server create --image trusty-server-cloudimg-amd64-nov4-2016 --flavor nodepool --nic net-id=private --security-group docker --user-data ./minikube/metadata minikube`

## ubuntu-base
`openstack server create --image trusty-server-cloudimg-amd64-nov4-2016 --flavor m1.medium --nic net-id=private --security-group default --user-data ./ubuntu-base/metadata ubuntu-base`

## about k8s dashboard
https://rominirani.com/tutorial-getting-started-with-kubernetes-on-your-windows-laptop-with-minikube-3269b54a226#.8g5ooypp1

