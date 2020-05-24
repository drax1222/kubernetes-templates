# kubernetes-templates
<br />
-- KUBERNETES --<br />
<OGOLNE> pods -> replica sets -> deployment<br />
kubectl cluster-info<br />
kubectl get deployments - lista diplojów<br />
kubectl get pods --namespace=kube-system - lista wszystkich w określonym namespace<br />
kubectl create -f file.yml - tworzenie pod`a<br />
kubectl delete pod nazwa_poda - usuwanie poda<br />
kubectl describe pod nazwa_poda // debug<br />
<LISTOWANIE><br />
kubectl get all - listuje wszystko pody/rs/deployments<br />
kubectl get pods <br />
kubtectl get rs<br />
kubtectl get deployments<br />
<SKALOWANIE><br />
kubectl scale --replicas=20 replicaset nazwa_setu - zwiększamy/zmniejszamy listę podów w aktualnie stojącym replicaset<br />
kubectl replace -f replicas.yml - "ładuje" plik yml do aktualnego rs`a<br />
