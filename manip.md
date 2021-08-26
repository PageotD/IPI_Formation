1. Copier le code dans VSC depuis le tuto Hashicorp
2. Créer un repo sur GitHub (peut importe le nom MAIS en publique)
3. git clone sur notre machine perso (pas container)
4. ensuite on stage, commit, on pull & push du code sur GitHub via VSC
5. on git clone le code sur le container
6. on lance Terraform init (quand ça fonctionnera)
7. on lance terraform apply
8. On met "yes"
9. On va sur Azure vérifier notre création de RG


1 ls
2 terraform version
3 az logout
4 az login
5 terraform init
6 terraform plan
7 terraform apply
8 terraform destroy -auto-approve
