## Kontrola vetraku
/proc/acpi/ibm/fan

## thermal things:
tlp

## deluge na raspi:

spustit tunel na raspi, kde bezi deluged
ssh -fNL 127.0.0.2:58846:localhost:58846 pi@sojka.tk -p 23

pote spustit klient Deluge a pripojit se na 127.0.0.2:58846 s loginem pi a heslem, ktere je uzivatelske na pi

## secure SOCKS5 proxy na server
ssh -D 1080 -f -C -q -N -p 22 USER@HOST

## hardware maintenance
[Official Lenovo HW maint manual](https://download.lenovo.com/pccbbs/mobiles_pdf/x1carbon_mt20fb-20fc_x1yoga_hmm_en_sp40j72016.pdf)

## pripojeni na Airport Time Capsule
sudo mount.cifs //192.168.0.234/Data /mnt/capsule -o password=asuswirelessrouterrtn16,sec=ntlm,vers=1.0
