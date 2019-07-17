# geo-ip.sh

Add ip geolotion lookup to bash script

## quickstart

```
{
  git clone git@github.com:temptemp3/geo-ip.sh.git
  geo-ip() { _(){ bash ${1}/${1} ${@:2} ; } ; _ ${FUNCNAME}.sh ${@} ; }
  geo-ip lookup 144.178.0.0
}
```
