794  cd workspace/ci_cd_lyesourred_ilyesdeochandiano/
  795  ls
  796  cd TD_GithubRunner/
  797  ls
  798  clear
  799  ls *
  800  lear
  801  cd
  802  nano .gitconfig 
  803  cd ./.ssh/
  804  ls
  805  cat id_ed25519_vm.pub 
  806  cd ~/workspace/ci_cd_lyesourred_ilyesdeochandiano/
  807  ls
  808  clear
  809  cd TD_GithubRunner/
  810  clear
  811  cd ..
  812  ls
  813  mv TD_GithubRunner/ ..
  814  cd ..
  815  ls
  816  clear
  817  ls
  818  cd TD_GithubRunner/
  819  ls -la
  820  cd ..
  821  git init TD_GithubRunner/
  822  cd TD_GithubRunner/
  823  ls
  824  git status
  825  git add docker-compose.yml index.php journal.md 
  826  git commit -m "TP GitHub Runner initiate the project with Dat src"
  827  git push origin master 
  828  git push 
  829  git remote add TP_GithubRunner git@github.com:LyesOrd/TP_GithubRunner.git
  830  git push 
  831  git push --set-upstream TP_GithubRunner master
  832  eval `ssh-agent -s`
  833  ssh-add ~/.ssh/id_ed25519_vm
  834  git push --set-upstream TP_GithubRunner master
  835  clear
  836  docker ps
  837  cd ../ci_cd_lyesourred_ilyesdeochandiano/TD_Proxy/
  838  ls
  839  cat docker-compose.yml
  840  nano docker-compose.yml
  841  cd ..
  842  cd TD_GithubRunner/
  843  ms
  844  ls
  845  docker ps
  846  docker stop td_proxy-phpmyadmin-1 
  847  clear
  848  curl localhost:81
  849  curl localhost:81/index.php
  850  ls
  851  cat docker-compose.yml 
  852  nano docker-compose-runner.yml
  853  docker pull myoung34/github-runner
  854  mkdir actions-runner && cd actions-runner
  855  curl -o actions-runner-linux-x64-2.317.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.317.0/actions-runner-linux-x64-2.317.0.tar.gz
  856  echo "9e883d210df8c6028aff475475a457d380353f9d01877d51cc01a17b2a91161d  actions-runner-linux-x64-2.317.0.tar.gz" | shasum -a 256 -c
  857  tar xzf ./actions-runner-linux-x64-2.317.0.tar.gz
  858  ./config.sh --url https://github.com/LyesOrd/TP_GithubRunner --token AN64R7WCKPXLPEC5NXPKYL3GONM4C
  859  ./run.sh
  860  clear
  861  ls
  862  cd externals/
  863  ls
  864  cd ..
  865  ls
  866  clear
  867  ls
  868  ./config.sh --url https://github.com/LyesOrd/TP_GithubRunner --token GITHUB_RUNNER
  869  docker ps
  870  exitr
  871  exit
  872  cd workspace/
  873  ls
  874  cd TD_GithubRunner/
  875  ls
  876  cd actions-runner/
  877  ls
  878  clear
  879  cd ..
  880  cd actions-runner/
  881  ls
  882  cd ..
  883  ls
  884  cat docker-compose.yml 
  885  cd ..
  886  ls
  887  cd TD_GithubRunner/
  888  cd ../ci_cd_lyesourred_ilyesdeochandiano/
  889  ls
  890  mkdir TD_GithubRunner
  891  cd TD_GithubRunner/
  892  ms
  893  ls
  894  rm -rf .*
  895  ls
  896  rm -rf *
  897  sudo rm -rf *
  898  ls
  899  clear
  900  ls -la
  901  vim docker-compose.yml
  902  ls
  903  ls ..
  904  mv ../compose ./
  905  sudo mv ../compose ./
  906  ls
  907  ls -la
  908  sudo chown user:user .
  909  ls -la
  910  mv compose docker-compose.yml
  911  ls
  912  cat docker-compose.yml 
  913  docker compose up -d
  914  docker logs td_githubrunner-worker-1 
  915  nano docker-compose.yml 
  916  docker compose up -d
  917  doc
  918  docker logs td_githubrunner-worker-1 
  919  clear
  920  ls
  921  cd ..
  922  ls
  923  cd TD_DO
  924  cd TD_Docker
  925  cd TD_DockerCompose/
  926  ls
  927  clear 
  928  cd ..
  929  ls
  930  cd TD_GithubRunner/
  931  ls
  932  cd ../..
  933  ls
  934  cd TD_GithubRunner/
  935  ls
  936  mkdir .workflows
  937  cd .workflows/
  938  touch ci.yml
  939  nano ci.yml 
  940  cd ..
  941  ls
  942  cd ..
  943  ls
  944  clear
  945  git status
  946  git add .github/.workflows/ci.yml 
  947  git commit -m "add ci workflow"
  948  git push origin master
  949  eval `ssh-agent -s`
  950  ssh-add ~/.ssh/id_ed25519_vm
  951  git push origin master
  952  git push 
  953  ls
  954  cd .git
  955  ls
  956  cd ..
  957  ls
  958  ls -la
  959  cd .github/
  960  ls
  961  cd .workflows/
  962  ls
  963  cat ci.yml 
  964  cd ..
  965  mv .workflows/ workflows
  966  ls
  967  cd ..
  968  git add .github/
  969  git commit -m "add ci"
  970  git push
  971  nano .github/workflows/ci.yml 
  972  git add .github/
  973  git commit -m "add ci"
  974  git push
  975  docker ps
  976  docker compose down
  977  docker ps
  978  docker stop td_proxy-phpmyadmin-1 
  979  dockeros
  980  docker ps
  981  git add .github/
  982  git commit -m "test curl workflow"
  983  git push
  984  nano .github/workflows/ci.yml 
  985  git add .github/
  986  git commit -m "test curl workflow"
  987  git push
  988  nano .github/workflows/ci.yml 
  989  git add .github/
  990  git commit -m "test curl workflow"
  991  git push
  992  curl localhost:81
  993  nano .github/workflows/ci.yml 
  994  clear
  995  git add .github/
  996  git commit -m "test curl workflow"
  997  git push
  998  curl localhost:81
  999  docker ps
 1000  nano .github/workflows/ci.yml 
 1001  curl localhost:81
 1002  docker ps
 1003  ls
 1004  cat docker-compose.yml 
 1005  clear
 1006  docker compose up
 1007  docker compose up -d
 1008  docker ps
 1009  curl localhost:81
 1010  curl localhost:81/index.php
 1011  nano .github/workflows/ci.yml 
 1012  git add .github/
 1013  git commit -m "test curl workflow"
 1014  git push
 1015  docker compose down
 1016  clear
 1017  docker ps
 1018  nano .github/workflows/ci.yml 
 1019  ls
 1020  git add .github/
 1021  git commit -m "test curl workflow"
 1022  git push
 1023  curl localhost:81/index.php
 1024  nano .github/workflows/ci.yml 
 1025  clear
 1026  git add .github/
 1027  git commit -m "test curl workflow"
 1028  git push
 1029  docker compose up -d
 1030  curl localhost:81
 1031  curl localhost:81/index.php
 1032  clear
 1033  ls
 1034  curl localhost:81/index.php
 1035  docker compose logs -f
 1036  docker ps
 1037  docker logs nginx 
 1038  clear
 1039  curl localhost:81/index.php
 1040  docker ps
 1041  curl localhost:81/index.php
 1042  docker exec td_githubrunner-worker-1 bash
 1043  docker exec td_githubrunner-worker-1 sh
 1044  docker exec -it td_githubrunner-worker-1 sh
 1045  nano .github/workflows/ci.yml 
 1046  cat .github/workflows/ci.yml 
 1047  git add .github/
 1048  git commit -m "test curl workflow"
 1049  git push
 1050  docker compose down
 1051  docker ps
 1052  docker exec -it nginx curl localhost:81/index.php
 1053  docker exec nginx curl localhost:81/index.php
 1054  docker exec -it td_githubrunner-worker-1 sh
 1055  docker exec -it nginx sh
 1056  clear
 1057  docker ps
 1058  docker exec nginx curl localhost:81/index.php
 1059  docker exec nginx curl localhost:80/index.php
 1060  nano .github/workflows/ci.yml 
 1061  git add .github/
 1062  git commit -m "test curl workflow"
 1063  git push
 1064  nano .github/workflows/ci.yml 
 1065  git add .github/
 1066  git commit -m "test curl workflow"
 1067  git push
 1068  clear
 1069  ls
 1070  history 
