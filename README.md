# Setup Instructions


```
$ conda create -n tmpsf python=2 ipykernel requests thredds_crawler xarray netcdf4 pandas numpy matplotlib
```


To add the `tmpsf` environment to jupyter as a selectable kernel

```
$ python -m ipykernel install --user --name tmpsf

```
