  506  git push 
  507  ssh-add ~/.ssh/id_ed25519_vm
  508  git push 
  510  mkdir TD_GithubRunner
  511  cd TD_GithubRunner/
  512  ls
  513  vim docker-compose.yml
  514  cat index.php 
  515  ls
  516  cat index.php 
  517  cat InitDB.sql 
  518  ls
  519  nano docker-compose.yml
  520  docker ps
  521  docker stop td_proxy-phpmyadmin-1 td_proxy-app-1 td_proxy-db-1 
  522  docker-compose up -d
  523  docker compose up -d
  524  docker ps
  525  sudo docker ps
  526  sudo docker compose up -d
  527  docker ps -a
  528  mkdir -p docker-web/www
  529  mkdir -p docker-web/log 
  530  touch docker-web/log/{error,access}.log
  531  sudo touch docker-web/log/{error,access}.log
  532  chmod a+rw docker-web/log/*
  533  sudo chmod a+rw docker-web/log/*
  534  ls
  535  .nginx-conf
  536  nano .nginx-conf
  537  cat .nginx-conf 
  538  docker compose up -d
  539  ls
  540  cd docker-web/
  541  ls
  542  mv log/ nginx.conf/ www/ ..
  543  sudo mv log/ nginx.conf/ www/ ..
  544  ls
  545  cd ..
  546  rm -rf docker-
  547  rm -rf docker-web/
  548  ls
  549  clear
  550  ls
  551  cat nginx.conf/
  552  cd nginx.conf/
  553  ls
  554  ls -la
  555  cd ..
  556  ls
  557  mv .nginx-conf nginx.conf/
  558  sudo mv .nginx-conf nginx.conf/
  559  ls -la
  560  docker compose up -d
  561  nano docker-
  562  nano docker-compose.yml 
  563  docker compose up -d
  564  nano docker-compose.yml 
  565  cd /etc/
  566  ls
  567  ls -l /home/user/workspace/ci_cd_lyesourred_ilyesdeochandiano/TD_GithubRunner/nginx.conf
  568  cd
  569  clear
  570  ls -l /home/user/workspace/ci_cd_lyesourred_ilyesdeochandiano/TD_GithubRunner/nginx.conf
  571  grep nginx
  572  clear
  573  cd workspace/ci_cd_lyesourred_ilyesdeochandiano/
  574  cd TD_GithubRunner/
  575  ls
  576  cd docker-web/
  577  ls
  578  cd ..
  579  ls
  580  rm -rf docker-web/
  581  sudo rm -rf docker-web/7
  582  sudo rm -rf docker-web/
  583  ls
  584  docker ps
  585  docker ps -a
  586  docker rm f231b3009530
  587  docker ps -a
  588  clea
  589  clear
  590  docker compose up -d
  591  cat docker-compose.yml 
  592  ls
  593  cd www/
  594  ls
  595  cd ..
  596  ls
  597  rm -rf log/ nginx.conf/ www/
  598  sudo rm -rf log/ nginx.conf/ www/
  599  ls
  600  rm -rf docker-compose.yml 
  601  docker pull linuxserver/nginx
  602  ls
  603  docker ps
  604  docker ps -a
  605  clear
  606  docker run -d --name=nginx -p 80:80 -p 443:443
  607  docker run -d --name=nginx -p 80:80 -p 443:443 --restart
  608  docker run -d --name=nginx -p 80:80 -p 443:443
  609  docker run -d 
  610  docker run --help
  611  docker run -h nginx
  612  clear
  613  docker run -d --name my-nginx -p 80:80 linuxserver/nginx
  614  docker ps
  615  docker stop my-nginx 
  616  docker rm my-nginx 
  617  docker ps
  618  docker run -d --name nginx-github-runner -p 80:80 linuxserver/nginx
  619  docker ps
  620  exit
  621  clear
  622  cd /home/user/appdata/mariadb/
  623  ls
  624  mv inidb initdb
  625  ls
  626  cat initdb 
  627  ls
  628  cd databases/
  629  ls
  630  cd ..
  631  ls
  632  cd
  633  clear
  634  cd workspace/ci_cd_lyesourred_ilyesdeochandiano/
  635  ls
  636  cd TD_GithubRunner/
  637  pwd
  638  clear
  639  ls
  640  clear
  641  ls
  642  cd mysql/
  643  s
  644  ls
  645  cd databases/
  646  ls
  647  cd mysql/
  648  ls
  649  clear
  650  docker ps -a
  651  cldear
  652  clear
  653  cd ../..
  654  ls
  655  cd ..
  656  clear
  657  ls
  658  cd mysql/
  659  ls
  660  cd databases/
  661  ls
  662  cd my
  663  cd mydata/
  664  ls
  665  cat db.opt 
  666  clear
  667  cd ../
  668  ls
  669  cd ..
  670  ls
  671  clear
  672  docker compose exec mariadb mysql mydata -u user -puser
  673  docker compose exec mariadb bash
  674  ls
  675  clear
  676  ls
  677  cd 
  678  cd /
  679  ls
  680  cd usr/
  681  ls
  682  cd ..
  683  ls
  684  var/
  685  cd var/
  686  ls
  687  cd ..
  688  cd etc/
  689  ls
  690  cd concd ..
  691  clea
  692  clear
  693  cd
  694  exit
  695  df -h
  696  clear
  697  cd workspace/ci_cd_lyesourred_ilyesdeochandiano/
  698  ls
  699  clear
  700  ls
  701  cd TD_GithubRunner/
  702  ls
  703  git status
  704  cd ../TD_DockerCompose/
  705  git restore docker-compose.yml Dockerfile 
  706  clear
  707  cd ../TD_GithubRunner/
  708  git status
  709  git logs
  710  git log
  711  clear
  712  ls
  713  history >> journal.md
