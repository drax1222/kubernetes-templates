# kubernetes-templates

-- KUBERNETES --
<OGOLNE> pods -> replica sets -> deployment
kubectl cluster-info
kubectl get deployments - lista diplojów
kubectl get pods --namespace=kube-system - lista wszystkich w określonym namespace
kubectl create -f file.yml - tworzenie pod`a
kubectl delete pod nazwa_poda - usuwanie poda
kubectl describe pod nazwa_poda // debug
<LISTOWANIE>
kubectl get all - listuje wszystko pody/rs/deployments
kubectl get pods 
kubtectl get rs
kubtectl get deployments
<SKALOWANIE>
kubectl scale --replicas=20 replicaset nazwa_setu - zwiększamy/zmniejszamy listę podów w aktualnie stojącym replicaset
kubectl replace -f replicas.yml - "ładuje" plik yml do aktualnego rs`a
