## Objetivo 
The password for the next level is stored in a file called **spaces in this filename** located in the home directory
## Datos de acceso al nivel 

user: bandit2
pass: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Solución  
`C:\Users\hoydw>ssh bandit2@bandit.labs.overthewire.org -p 2220`
                         `_                     _ _ _`
                        `| |__   __ _ _ __   __| (_) |_`
                        `| '_ \ / _ | '_ \ / _ | | __|`
                        `| |_) | (_| | | | | (_| | | |_`
                        `|_.__/ \__,_|_| |_|\__,_|_|\__|`


                      `This is an OverTheWire game server.`
            `More information on http://www.overthewire.org/wargames`

`bandit2@bandit.labs.overthewire.org's password:`

      `,----..            ,----,          .---.`
     `/   /   \         ,/   .`|         /. ./|`
    `/   .     :      ,`   .'  :     .--'.  ' ;`
   `.   /   ;.  \   ;    ;     /    /__./ \ : |`
  `.   ;   /   ; .'___,/    ,' .--'.  '   \' .`
  `;   |  ; \ ; | |    :     | /___/ \ |    ' '`
  `|   :  | ; | ' ;    |.';  ; ;   \  \;      :`
  `.   |  ' ' ' : ----'  |  |  \   ;        |`
  `'   ;  \; /  |     '   :  ;   .   \    .\  ;`
   `\   \  ',  /      |   |  '    \   \   ' \ |`
    `;   :    /       '   :  |     :   '  |--"`
     `\   \ .'        ;   |.'       \   \ ;`
  `www. --- ver     '---' he       '---" ire.org`


`Welcome to OverTheWire!`

`If you find any problems, please report them to the #wargames channel on`
`discord or IRC.`

`--[ Playing the games ]--`

  `This machine might hold several wargames.`
  `If you are playing "somegame", then:`

    `* USERNAMES are somegame0, somegame1, ...`
    `* Most LEVELS are stored in /somegame/.`
    `* PASSWORDS for each level are stored in /etc/somegame_pass/.`

  `Write-access to homedirectories is disabled. It is advised to create a`
  `working directory with a hard-to-guess name in /tmp/.  You can use the`
  `command "mktemp -d" in order to generate a random and hard to guess`
  `directory in /tmp/.  Read-access to both /tmp/ is disabled and to /proc`
  `restricted so that users cannot snoop on eachother. Files and directories`
  `with easily guessable or short names will be periodically deleted! The /tmp`
  `directory is regularly wiped.`
  `Please play nice:`

    `* don't leave orphan processes running`
    `* don't leave exploit-files laying around`
    `* don't annoy other players`
    `* don't post passwords or spoilers`
    `* again, DONT POST SPOILERS!`
      `This includes writeups of your solution on your blog or website!`

`--[ Tips ]--`

  `This machine has a 64bit processor and many security-features enabled`
  `by default, although ASLR has been switched off.  The following`
  `compiler flags might be interesting:`

    `-m32                    compile for 32bit`
    `-fno-stack-protector    disable ProPolice`
    `-Wl,-z,norelro          disable relro`

  `In addition, the execstack tool can be used to flag the stack as`
  `executable on ELF binaries.`

  `Finally, network-access is limited for most levels by a local`
  `firewall.`

`--[ Tools ]--`

 `For your convenience we have installed a few useful tools which you can find`
 `in the following locations:`

    `* gef (https://github.com/hugsy/gef) in /opt/gef/`
    `* pwndbg (https://github.com/pwndbg/pwndbg) in /opt/pwndbg/`
    `* peda (https://github.com/longld/peda.git) in /opt/peda/`
    `* gdbinit (https://github.com/gdbinit/Gdbinit) in /opt/gdbinit/`
    `* pwntools (https://github.com/Gallopsled/pwntools)`
    `* radare2 (http://www.radare.org/)`

`--[ More information ]--`

  `For more information regarding individual wargames, visit`
  `http://www.overthewire.org/wargames/`

  `For support, questions or comments, contact us on discord or IRC.`

  `Enjoy your stay!`



`Broadcast message from bandit2@bandit (pts/83) (Tue Aug 27 17:24:55 2024):`


`you can say hi with wall hi command.`


`hi`
`Command 'hi' not found, but can be installed with:`
`snap install hi`
`Please ask your administrator.`


`Broadcast message from bandit2@bandit (pts/83) (Tue Aug 27 17:25:12 2024):`


`hello`


`cat "spaces in thicat "spaces in this filename"`
`MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx`


`Broadcast message from bandit2@bandit (pts/58) (Tue Aug 27 17:25:37 2024):`


`shy?`


## Notas Adicionales 




### Referencias