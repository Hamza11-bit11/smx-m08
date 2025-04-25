# 📂 Pràctica 2 - Gestors d'Arxius Web

## 🧠 Sobre aquesta pràctica

Aquesta pràctica forma part de l’assignatura i tracta sobre com configurar un sistema de gestió d’arxius al núvol utilitzant **ownCloud** i una màquina virtual creada amb **IsardVDI**. El principal objectiu és entendre com funcionen aquests sistemes, aprendre a instal·lar-los, configurar-los i provar com es poden utilitzar per compartir fitxers entre diferents usuaris i dispositius.

---

## 🗃️ Contingut del projecte

A la carpeta trobaràs els següents fitxers:

| Fitxer              | Descripció                                                                 |
|---------------------|----------------------------------------------------------------------------|
| `INSTALLATION.md`   | Manual pas a pas per instal·lar IsardVDI, crear la màquina virtual i posar ownCloud. |
| `CONFIGURATION.md`  | Guia amb la configuració d'usuaris, permisos, compartició i proves d'ús.   |
| `README.md`         | Aquest fitxer, amb una vista general del projecte.                         |

---

## 🛠️ Tecnologies utilitzades

- 💻 **IsardVDI** – Per virtualitzar el sistema.
- ☁️ **ownCloud** – El gestor d’arxius que s’ha instal·lat.
- 🐧 **Ubuntu Server 22.04** – El sistema operatiu de la màquina virtual.
- 🔧 **Apache** + **MariaDB** – Per fer funcionar ownCloud al servidor web.
- 🖥️ **Client local** – Per accedir al sistema ownCloud remotament.

---

## 📷 Captures de pantalla

Tant a l’`INSTALLATION.md` com al `CONFIGURATION.md` hi he posat captures per veure tot el procés. Des de la instal·lació fins a les proves de compartir arxius amb rols diferents.

---

## ✅ Què s’ha fet

- Instal·lació d’una màquina virtual amb IsardVDI.
- Instal·lació completa d’ownCloud amb Apache i MariaDB.
- Creació de 3 usuaris amb rols diferents: admin, editor i visualitzador.
- Proves de pujar fitxers, crear carpetes i compartir contingut.
- Configuració d’enllaços amb caducitat i accés remot des d’altres dispositius.

---

## ⚠️ Observacions / Problemes

- Algun petit problema amb la xarxa de la màquina virtual (no pillava IP), però ho vaig solucionar posant-la en mode "Bridged".
- El rendiment d’ownCloud dins la VM no és súper ràpid, però funciona prou bé per les proves.
- En accedir des d’un altre dispositiu, cal assegurar-se que el tallafocs no bloquegi el port 80.

---

## 🔄 Extra (opcional)

Tot i que no era obligatori, vaig intentar configurar l'accés a ownCloud des de la meva màquina principal i també provar la connexió a altres núvols (companys de classe), però només ho vaig provar en local.

---

## 📦 Format d'entrega

El projecte està comprimit en un fitxer `.zip` amb el següent format:

```bash
NOM-COGNOM-PT2.zip

![imatge](https://github.com/user-attachments/assets/6fbb381d-a5e0-46d0-8a7b-a0a827ddc33e)
![imatge](https://github.com/user-attachments/assets/1660c0f2-eab0-42d2-87aa-66936f2bf28f)
