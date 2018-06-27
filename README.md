# OCL (oc login)

## Installing

    cd ~
    git clone https://github.com/openshift-cs/ocl
    pip install -r ocl/requirements.txt
    echo "export PATH=$(pwd)/ocl:\$PATH" >> ~/.bash_profile && source ~/.bash_profile

## Environment Variables

+ OCL_USERNAME: the username to use when logging in to clusters to support cli login

        echo "export OCL_USERNAME=<username>" >> ~/.bash_profile && source ~/.bash_profile

+ OCL_NAMESPACE: the namespace to automatically attempt to select upon successful login

        echo "export OCL_NAMESPACE=<namespace>" >> ~/.bash_profile && source ~/.bash_profile