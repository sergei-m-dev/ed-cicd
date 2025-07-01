PAT2: 

ssh ed-cicd

export CR_PAT=PAT

echo $CR_PAT | docker login ghcr.io -u sergei-m-dev --password-stdin