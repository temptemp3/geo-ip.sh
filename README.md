# geo-ip.sh

Add ip geolocation lookup to bash script

## quickstart

```
{
  git clone git@github.com:temptemp3/geo-ip.sh.git
  ( cd geo-ip.sh ; git clone https://github.com/temptemp3/sh2.git -b 190607 )
  chmod +x geo-ip.sh/geo-ip.sh
  geo-ip() { _(){ ${1}/${1} ${@:2} ; } ; _ ${FUNCNAME}.sh ${@} ; }
  geo-ip lookup 144.178.0.0
}
```

## install

```
{
  cat >> ~/.bashrc << EOF
######################################################################
## added $( date "+%d %b %Y" )
######################################################################
geo-ip() { _(){ \${1}/\${1} \${@:2} ; } ; _ \${FUNCNAME}.sh \${@} ; }
######################################################################
EOF
```
