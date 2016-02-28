# sdc-smartos
scripts, etc, to make using SDC a little easier for UNIX admins

vmuid - prints UUID of VM where arg is a RE that is matched in the output of 'vmadm list'
        usage:  vmuid foo
                vmuid ^foo
                vmuid ^foo0$
                
vmifcreate - shell wrapper around the js example in the docs for vmadm to create a nic
        usage:  run with -h for docs

vmifdel - undo vmifcreate
