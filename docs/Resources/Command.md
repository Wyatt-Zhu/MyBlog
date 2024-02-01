# Command
## conda

### env

#### create env

``` sh
conda create -n name python=
```

#### remove env

```sh
conda remove -n name --all
```



## jupyter

### kernel

#### add kernel

```sh
python -m ipykernel install --user --name kernel_name
```

#### remove kernel

```sh
jupyter kernelspec remove kernel_name
```

#### show kernel list

```sh
jupyter kernelspec list
```

