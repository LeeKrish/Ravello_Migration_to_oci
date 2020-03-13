#!/usr/bin/env bash
sudo su -
!mount
read BluePrint_IMG
cd /staging
qemu-img convert -O qcow2 -p /dev/vdc /stagging/$BluePrint_IMG.qcow2 && oci os object put -bn Ravello_Migrated_Images --file /stagging/$BluePrint_IMG.qcow2 --name $BluePrint_IMG.qcow2 --mutipart

