Documentation of the base image : https://hub.docker.com/r/jenkins/inbound-agent

docker build . -t jenkins_agent_symfony

docker run --name jenkins_agent_symfony_container --init jenkins_agent_symfony -url http://172.17.0.2:8080 23369578a9ea856319ab685e2729d92ea4274914195413d0b7dc3de66ee76f16 JenkinsAgent_composer

To get the <IPAdresse_of_jenkins_master>, make this command :
docker inspect jenkins_master_container

<password> and <node_name> are given by the jenkins_master when you create a node#   J e n k i n s - a g e n t 
 
 