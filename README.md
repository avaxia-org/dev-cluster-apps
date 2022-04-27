# dev-cluster-apps
apps ins app

1- be in the context where argocd is installed '
2- argocd login 20.212.131.76:80 (adress load balancer : port )
3- add user password
4- argocd cluster add dev-cluster  (context name)


Deploy on remote cluster

1-very important : Deploy argocd instance cd on the remote cluster too because CRD are needed so the cluster can receive the deployment.


