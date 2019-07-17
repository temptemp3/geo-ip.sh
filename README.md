# geo-ip.sh

Add ip geolotion lookup to bash script

## quickstart

```
{
  git clone git@github.com:temptemp3/geo-ip.sh.git
  chmod +x geo-ip.sh/geo-ip.sh
  geo-ip() { _(){ ${1}/${1} ${@:2} ; } ; _ ${FUNCNAME}.sh ${@} ; }
  geo-ip lookup 144.178.0.0
}
```
