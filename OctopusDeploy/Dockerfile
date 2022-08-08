FROM octopusdeploy/octopusdeploy:2022.2.7692

USER root
RUN /usr/bin/curl -fsSLo /usr/local/bin/kubectl "https://dl.k8s.io/release/$(/usr/bin/curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
RUN chmod 755 /usr/local/bin/kubectl
