# Learn Ocaml , a pathway 

in this repository , i will try to post every code i wrote in my pathway to learn Ocaml  

## Setting up the environment 
Installing **Ocaml** compiler is a bit sketchy in both mac and windows but the ways i will are the ones that i found easy to follow !
### For windows
-to install the enviroment i follow this [blog](https://titiandragomir.wordpress.com/2017/09/27/instalarea-ocaml-si-visual-studio-code) with a video attached , or you can install (wincaml,maccaml,unixcaml) [link](https://jean-mouric.pagesperso-orange.fr) or simply follow this video [blog](https://youtu.be/xTsHMja8joA)
###  For Mac OS
the best way i find to install ocaml in mac is using [homebrew](https://brew.sh/index_fr)  , that can be installed easily by following the link provided.
then running this commands on Terminal
```shell
brew install ocaml
```
```shell
brew install opam
```
## Running your First Ocaml program on your environment in terminal (to make sure everything is ok ! )
Let's first create our new file with extension *.ml* then write 
```
print_string "Hello World !";
```
then we compile using this command line
```
ocamlc -o name filename.ml
```
then we can execute 
```
./name
```
