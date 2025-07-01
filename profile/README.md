# PokerBots Borås

Detta är organisationssidan för tävlingen [PokerBots Borås](http://www.pokerbotsboras.grgta.xyz), anordnad i juli 2025 för SUVNET på YH i Borås.

![PokerBotsLogo_small](https://github.com/user-attachments/assets/7fa9bef5-a1a2-49bd-95ed-4b8eb9f80132)



## Kom igång snabbt

1. Om du inte redan gjort det, gå till [pokerbotsboras.grgta.xyz](https://pokerbotsboras.grgta.xyz) och anmäl dig.
2. Vänta 10 minuter så får du ett repo med en template för en bot som du kan börja med.
3. Följ instruktionerna i README-filen för att submitta din bot.

---

### Använda något annat än C\#

Om du vill skapa en bot som inte använder C#, gå till:
👉 [BotTemplate.Docker](https://github.com/PokerBotsBoras/BotTemplate.Docker)
Följ instruktionerna i repots README för att skapa din egen template.

---

## Regler Pokervarianten

**Heads-Up Micro Hold’em** är en förenklad, snabb pokervariant där varje spelare får ett privat kort och delar ett gemensamt. Det gör varje beslut viktigt – strategi, bluffar och sannolikhetsbedömning står i fokus.

Spelet spelas alltid 1 mot 1 ("heads-up"). Reglerna är enkla att implementera men tillräckligt komplexa för intressant botlogik.

👉 Läs de fullständiga reglerna här:
[PokerRules.md](https://github.com/PokerBotsBoras/PokerBots-Docs/blob/main/PokerRules.md)

---

## Tournament Runner

👉 [TournamentRunner](https://github.com/PokerBotsBoras/TournamentRunner)

Här körs bottarna mot varandra. Det kan vara värt att kolla på för att förstå flödet i spelet.

Studera det gärna – särskilt:

* `PokerEngine`: visar hur en enskild hand körs.
* `TournamentRunner`: hanterar flera händer i följd.

Turneringen körs en gång i timmen. Resultat visas på:
[pokerbotsboras.grgta.xyz/ratings.html](https://pokerbotsboras.grgta.xyz/ratings.html)
Ledartavlan bygger på ELO-rating ([Wikipedia](https://en.wikipedia.org/wiki/Elo_rating_system)).

---

## TemplateBot

👉 [BotTemplate](https://github.com/PokerBotsBoras/BotTemplate)

Detta repo är vad varje deltagare får efter anmälan.

---



