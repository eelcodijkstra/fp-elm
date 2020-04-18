# Hoe te installeren?

1. installeren van elm: https://github.com/elm/compiler/blob/master/installers/linux/README.md

curl -L -o elm.gz https://github.com/elm/compiler/releases/download/0.19.1/binary-for-linux-64-bit.gz
gunzip elm.gz
chmod +x elm
mkdir .local/bin
mv elm .local/bin/

2. installeren van elm-kernel:

python -m elm_kernel.install

* (kan dat in de postBuild, of moet dat steeds bij het opstarten van de binder?)
