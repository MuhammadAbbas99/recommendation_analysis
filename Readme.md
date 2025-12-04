https://surpriselib.com/

https://www.anaconda.com/download

- Download Miniconda Installer
(sivun lopussa)
- Windows-koneelle
- Asenna anaconda oletusten 
mukaan koneelle
- Avaa Anaconda Prompt


# Komentoja promptissa

https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html

cd Desktop

mkdir suosittelu

cd suosittelu

code . (-> avaa visual studio coden oikeassa paikassa)

conda create -n surprise-env python=3.11

conda activate surprise-env

conda install -c conda-forge scikit-surprise

conda install -n surprise-env ipykernel --update-deps --force-reinstall

conda install --name surprise-env pandas
    # use this command to install every missing package

# Tarkista ympäristö 

conda info --envs

• (surprise-env) C:\ma053309\Desktop\suosittelu>conda info --envs


• # conda environments:

• #

• # * -> active

• # + -> frozen

• base C:\Users\ma053309\Desktop\suosittelu>

• surprise-env * C:\ma053309\AppData\Local\miniconda3\envs\surprise-env


# poista condan virtuaalikansio

conda env remove -n surprise-env
