# SSL Error:

**PROXY PROBLEM**

## to install a package: --trusted-host page_URL

pip install --trusted-host files.pythonhosted.org poetry


## To install requirements.txt (pip frezze command output)

pip install --trusted-host files.pythonhosted.org -r requirements.txt

-----------------------------

## Anaconda environment creation - SSL error

In anaconda prompt: 

conda config --set ssl_verify false 

À partir de l’adresse <https://stackoverflow.com/questions/33699577/conda-update-fails-with-ssl-error-certificate-verify-failed> 

------------------------------

# Proxy

File .condarc 

conda config --set proxy_servers.http http://id:pw@address:port

conda config --set proxy_servers.https https://id:pw@address:port

conda config --set HTTP_PROXY=http://id:pw@address:port

conda config --set HTTPS_PROXY=https://id:pw@address:port

------------------------------

# Others 

python - 'Conda' is not recognized as internal or external command - Stack Overflow
