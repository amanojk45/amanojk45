history ---> selenium & docker setup ---->


/dev/loop1       56M   56M     0 100% /snap/core18/2344
/dev/loop2       27M   27M     0 100% /snap/amazon-ssm-agent/5163
tmpfs            98M     0   98M   0% /run/user/1000
ubuntu@ip-172-31-45-77:~/docker-selenium-new/target$ ls
FirmwareUpgrade-1.0-SNAPSHOT-jar-with-dependencies.jar  archive-tmp  generated-sources  maven-status
FirmwareUpgrade-1.0-SNAPSHOT.jar                        classes      maven-archiver     test-classes
ubuntu@ip-172-31-45-77:~/docker-selenium-new/target$ history
    1  ls
    2  sudo apt-get update
    3  sudo apt-get install docker.io
    4  sudo apt-get install openjdk-8-jdk
    5  java --version
    6  java -version
    7  maven
    8  sudo apt install maven
    9  df -h
   10  ls
   11  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
   12  sudo apt install ./google-chrome-stable_current_amd64.deb
   13  ls
   14  cat /etc/apt/sources.list.d/google-chrome.list
   15  google-chrome --version
   16  ls
   17  wget https://chromedriver.storage.googleapis.com/101.0.4951.41/chromedriver_linux64.zip
   18  ls
   19  sudo unzip chromedriver_linux64.zip
   20  sudo apt-get install unzip
   21  ls
   22  sudo unzip chromedriver_linux64.zip
   23  ls
   24  chromedriver --version
   25  chromedriver -version
   26  chromedriver --version
   27  sudo mv chromedriver /usr/bin/chromedriver
   28  sudo chown root:root /usr/bin/chromedriver
   29  sudo chmod +x /usr/bin/chromedriver
   30  chromedriver --version
   31  ls
   32  java -version
   33  sudo docker --version
   34  DOCKER_CONFIG=${DOCKER_CONFIG:-$HOME/.docker}
   35  mkdir -p $DOCKER_CONFIG/cli-plugins
   36  curl -SL https://github.com/docker/compose/releases/download/v2.4.1/docker-compose-linux-x86_64 -o $DOCKER_CONFIG/cli-plugins/docker-compose
   37  chmod +x $DOCKER_CONFIG/cli-plugins/docker-compose
   38  docker compose version
   39  ls
   40  git clone https://github.com/amanojk45/docker-selenium-new.git
   41  ls
   42  cd docker-selenium-new/
   43  ls
   44  cd target/
   45  ls
   46  cd ..
   47  ls
   48  sudo rm -f target/
   49  ls
   50  sudo rm -rf target/
   51  ls
   52  mvn clean build
   53  ls
   54  mvn clean test
   55  ls
   56  cd t
   57  cd target/
   58  ls
   59  cd classes/
   60  ls
   61  cd com/
   62  ls
   63  cd avin/
   64  ls
   65  cd ../../../..
   66  ls
   67  cd target/
   68  ls
   69  cd maven-status/
   70  s
   71  ls
   72  cd maven-compiler-plugin/
   73  ls
   74  cd compile/
   75  ls
   76  cd default-compile/
   77  ls
   78  cd ../../../../
   79  ls
   80  cd generated-sources/
   81  ls
   82  cd annotations/
   83  ls
   84  cd ../..
   85  ls
   86  cd ..
   87  ls
   88  sudo nano pom.xml
   89  ls
   90  sudo rm -f target/
   91  ls
   92  mvn clean test
   93  ls
   94  cd target/
   95  ls
   96  c ..
   97  cd ..
   98  ls
   99  sudo nano pom.xml
  100  mvn clean test
  101  ls
  102  mvn install -DskipTests=false
  103  ls
  104  cd target/
  105  ls
  106  df -h
  107  ls
  108  history
  
  
  https://github.com/amartanwar42/SeleniumGridUsingDocker.git
  https://medium.com/@amartanwar93/selenium-grid-using-docker-ab66f15c657b
  
  
  https://understandingdata.com/install-google-chrome-selenium-ec2-aws
  
  https://groups.google.com/d/msgid/selenium-users/87cbded2-8214-4943-958e-25648dea316c%40gmail.com
