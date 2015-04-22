
# bash note

##

執行

``` sh
dpkg --get-selections | grep bash
```

顯示

```
bash                                            install
bash-completion                                 install
bash-doc                                        install
```

執行

``` sh
$ dpkg -l | grep bash
```

顯示

```
ii  bash                                                        4.3-7ubuntu1.5                             amd64        GNU Bourne Again SHell
ii  bash-completion                                             1:2.1-4                                    all          programmable completion for the bash shell
ii  bash-doc                                                    4.3-7ubuntu1.5                             all          Documentation and examples for the The GNU Bourne Again SHell
ii  command-not-found                                           0.3ubuntu12                                all          Suggest installation of packages in interactive bash sessions
```

執行

```
$ man builtins
```


執行

```
$ man bash-builtins
```


