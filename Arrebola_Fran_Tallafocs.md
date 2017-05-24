
    Tallafocs
        Què es un sistema tallafocs? Quina és la seva finalitat?
	Es un sistema de seguretat de la xarxa. Monitoreja i controla la entrada i sortida del trafic de la xarxa.
        Quines generacions de tallafocs hi ha hagut i què millorava cadascun?
	3. Milloraba la col·locació dels paquets, i finalment van entrar en la capa d'aplicacio del model OSI
        Quines capes té el model OSI?
	1-Fisica
	2-Enllaç de dades
	3-Xarxa
	4-Transport
	5-Sessió
	6-Presentacio
	7-Aplicacio
	
        Quines capes té el model TCP/IP? En aquest cas feu una breu descripció de les funcionalitats de cada capa.
	1-Acces al medi: Direccionament fisic.
	2-Internet:  Determina la ruta i la IP
	3-Transport: Punt a punt i fiabilitat de dades.
	4-Aplicació: Serveis red a aplicacions i respresentacio de les dades.
        A quina capa/capes sol treballar tradicionalment un tallafocs?
	A la de transport i la de xarxa.


    Tallafocs Linux
    
        Busqueu quins són els tradicionals sistemes de tallafocs incorporats en linux i anomeneu-los
	Iptables
	UFW
	FirewallD
	Fail2ban
	Firestarter
	
        Quins dels anteriors tallafocs estan instal.lats al fedora de classe? Com ho comproveu?
	FirewallD

        Algun dels anteriors tallafocs es troba activat?
	No, esta inactive,(dead)

        Instal.leu el servidor web httpd o nginx i activeu-ne el servei (dnf installl ...  ; systemctl ....). Indiqueu les comandes i comproveu que des d'una altra màquina podeu accedir via web a la vostra IP (digueu-li a un company). Hauria de sortir la plana per defecte.
        Activeu el servei firewalld. Indiqueu com ho feu.
	systemctl start firewalld

        Comproveu si ara es pot seguir accedint.
	No. 

    Win7
        Porta aquest SO algun tallafocs incorporat?
	Si. El firewall el porta de serie.
        Arrenqueu una màquina win7 a isard.escoladeltreball.org
        Indiqueu com arribar al tallafocs (passos i pantalles)


	Anem a inicio, panel de control, sistema y seguridad, firewall de windows.
	

	
        Es troba activat en aquest windows?
	Si, l'acabo de connectar.

        Busqueu un altre tallafocs per windows. Indiqueu la plana web i les prestacions que ens dona. Intenteu que NOMÉS sigui tallafocs.
	Zonealarm. Es un firewall profesional en el cual no s'ha de pagar de poder utilitzarlo. El protegeix dels malwares en xarxes publicas, en xarxes inhalambriques i s'actualitza a temps real.

https://www.zonealarm.com/es/software/free-firewall/

