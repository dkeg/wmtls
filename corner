#!/bin/sh

CUR=${2:-$(pfw)}
ROOT=$(lsw -r)
SW=$(wattr w $ROOT)
SH=$(wattr h $ROOT)

BW=$(wattr b $CUR)
W=$(wattr w $CUR)
H=$(wattr h $CUR)

#X=0
#Y=0
coord="70"
X=$coord
Y=$coord
num=$coord/$BW

case $1 in
    #tr) X=$((SW - W - BW*2)) ;;
    tr) X=$((SW - W - BW*$num)) ;;
    bl) Y=$((SH - H - BW*$num)) ;;
    br) X=$((SW - W - BW*$num))
        Y=$((SH - H - BW*$num)) ;;
    md) X=$((SW/2 - W/2 - BW))
        Y=$((SH/2 - H/2 - BW));;
esac

wtp $X $Y $W $H $CUR
