# TAKserver
Hahaha boom

Een project rondom het opzetten en testen van een TAK-server voor kaartdeling, communicatie en situational awareness in het veld. Gebaseerd op o.a. FreeTAKServer, Taky, CoT, Meshtastic, Mumble, en RedQueen plugins.

## 🔍 Doel
Een gebruiksvriendelijke en uitbreidbare setup creëren waarmee een team snel locaties, markers en berichten kan delen via ATAK/WINtak apps, ondersteund door een centrale server.

## 📁 Project Files
- [📄 GDrive: Quick Notes & Documentatie](https://drive.google.com/drive/folders/13sRu1AXh6CDP4ThazEPBKQfufQZNegkb)

## 📚 Documentatie
- [📘 CIV TAK Documentation](https://www.civtak.org/documentation/)
- [📕 WIN TAK Reddit Wiki](https://www.reddit.com/r/ATAK/wiki/index/)
- [📗 FreeTAKServer Docs](https://freetakteam.github.io/FreeTAKServer-User-Docs/)

## 🛠️ Tools & Technologieën
| Component        | Uitleg |
|------------------|--------|
| **FreeTAKServer** | Volledig uitgeruste TAK-server met CoT support. |
| **Taky**          | Lichtgewicht CoT-server met file sharing (Data Packages). |
| **ATAK/WINtak**   | Clientsoftware voor Android/Windows. |
| **CoT**           | Cursor-on-Target protocol voor positionele berichten. |
| **Meshtastic**    | Lora off-grid communicatie hardware (optioneel). |
| **Mumble**        | Voice chat met plugin-ondersteuning voor TAK. |
| **RedQueen**      | Text-to-Speech plugin voor audio meldingen. |
| **Podman/Docker** | Containerisatie van servercomponenten. |

## 🚀 Setup Snelstart

### VPS Gegevens

*bekend bij de redactie*

Webinterface: [Taky login](http://pewpatrol.nl:5000/login)

### FreeTAKServer Installatie
```bash
# Log in op de VPS
ssh root@91.99.202.190

# Systeem updaten
apt update && apt upgrade -y

# Afhankelijkheden installeren
apt install python3 python3-pip git -y

# Repo klonen en starten
git clone https://github.com/FreeTAKTeam/FreeTakServer.git
cd FreeTakServer
pip3 install -r requirements.txt
python3 FreeTAKServer.py
```

# Rekening houden met dat dit voornamelijk nog als documentatie dient en we nu weer vooralsnog Taky gebruiken.
