# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/pytraaa9-ai/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/pytraaa9-ai/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A program that writes one image summing up Monday 23 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story Ukraine sinks the Russian corvette Merkury off Libya, second story Russian strikes kill 14 around Kyiv, plus 48 more stories across six continents, a world map, and Friday's market close with Monday's Nikkei slide. Full-day edition, v1 — 50 stories.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** Ukraine sinks Russian corvette off Libya — Zelenskyy says seven sea drones sank the corvette Merkury at Benghazi on Sunday, hit the cargo ship MV Angara and destroyed a Ka-27 helicopter. Libya says two drones hit and four were intercepted; about 10 wounded.
- **Second story:** Russian strikes kill 14 around Kyiv — Dymer apartment block partly collapses, 10-11 dead, 14 missing; Vyshneve 3 dead; Bila Tserkva 1 dead.
- 153 drones overnight: Russia launches 153 drones; impacts at 11 sites; 2,471 troops lost in a day.
- Kerch Bridge crippled: Ukrainian strikes halt road traffic; only one rail track left open.
- Rylsk drone unit hit: Ukraine hits a Russian drone unit in Rylsk; an ammo depot detonates.
- Trilateral talks 'soon': Kremlin says a new Russia-US-Ukraine round is near, possibly in Abu Dhabi.
- Belgium strike chaos: National anti-austerity strike snarls transport; government fate in balance.
- Denmark: rapper murder plot: Russia accused of plotting to kill Ukrainian-American rapper Kyivstoner.
- Germany PMI surges: Factory activity hits its highest since March 2022.
- UK to build Ukraine drones: Britain to produce Ukrainian-designed strike drones under a new deal.
- Nuclear satellite feared: NATO intel: Russia plans to launch a satellite armed with a nuclear weapon.
- Zelenskyy: Putin a 'killer': Zelenskyy answers Trump calling Putin a 'friend': 'for us, he's a killer.'
- Rutte: NATO will defend Poland: NATO chief vows to defend every inch of Poland; allies meet in Brussels.
- French court: racist beating: Court recognises racist police beating of Michel Zecler; officers jailed.
- Manchester concert evacuated: Don Toliver show cleared after an unknown substance is released.
- Iran: 'all means' vs blockade: Tehran vows to use 'all available means' against the US naval blockade.
- Gaza: truck hit, 3 killed: Israeli forces hit a truck on Saturday; Oxfam warns 99% of Gaza is toxic.
- Eisenkot: 'Jewish terrorism': PM-elect condemns settler arson in Palestinian villages near Ramallah.
- Khartoum drones hit UN HQ: Drones from Ethiopia hit homes, the airport and a UN building; 3 killed.
- South Sudan: 24 civilians killed: Weekend attack in Tonj East kills 24, including 7 children.
- Libya: 'grave concern': Tripoli warns of conflict spilling into civilian ports after the strike.
- Senegal AFCON appeal: CAS to rule Tuesday on Senegal's appeal over its AFCON 2025 title.
- Banten fire: 24 dead: Candy-factory blaze toll confirmed; 30-34 still missing, 29 rescued.
- Korea: minister quits: Education chief resigns over AI cheating; first woman named spy chief.
- Hasina to be jailed if she returns: Dhaka: ex-PM faces arrest on return from India; death sentence stands.
- Thai MP: sentence cut to 3 years: Appeals court upholds royal-defamation conviction, halves the term.
- China warns off Mount Fuji: Beijing warns citizens off the mountain; $75,000 reward for a climber.
- China: death for spy official: Ministry official sentenced to death for espionage; AI-chip spy ring.
- India: $1.62bn for Nepal: New Delhi offers a recovery package to flood-hit Nepal.
- Chapo Isidro captured: Mexican military seizes Sinaloa cartel leader in a raid; 11 dead.
- Democrats win 258 House seats: Largest House majority in three decades; Trump curbs oversight.
- Vance won't say on Iran strikes: Vice-president declines to say if he would authorise strikes on Iran.
- Trump: tax overseas data centres: President vows to block US firms building data centres abroad.
- ICE detain father, daughter: Masked agents seize pair on a Seattle jet bridge; passengers film it.
- Judge keeps ICE-shot man jailed: Court refuses to free Oscar Belgal, shot by ICE agents in October.
- Hubbard beats Foxx by 330: Recount confirms Democrat ousts 11-term Republican in North Carolina.
- Army to detonate Iowa chemicals: Army invokes emergency powers to blow up bomb chemicals on Wednesday.
- Court strikes down pregnancy law: Appeals court voids workplace accommodation law for pregnant women.
- Trump downplays FBI breach: President shrugs off the breach of the FBI's crime database.
- Pentagon curbs Canada contact: Memo tells US troops to limit social contact with Canadian counterparts.
- Judge blocks triumphal arch: Second judge halts Trump's arch near Arlington National Cemetery.
- Delta: 1,600 flights delayed: Weight-data glitch snarls Delta flights in the Thanksgiving rush.
- SpaceX sued over AI safety: Oregon and Virginia sue Musk's firm over AI-tool safety claims.
- Meta: superintelligence: Executive warns artificial superintelligence is coming soon.
- UN AI weapons talks end: No binding rules on autonomous weapons; two years of talks agreed.
- Nvidia affair spy link: NYT: Jensen Huang's ex-lover kept contact with a Chinese spy official.
- SEC probing Nvidia accounts: Regulator scrutinises Nvidia's accounting practices, sources say.
- Brazil storm hits town: Deadly storm hits a town; thousands forced from their homes.
- Paredes collapses on air: Argentina star collapses during a post-match interview in Colombia.
- Vanuatu quake 6.5, no tsunami: Magnitude 6.5 quake strikes the Vanuatu region; no tsunami threat.

All stories were verified against at least two reputable sources
(Reuters, AP, AFP, BBC, Al Jazeera, UN News) on 23 November 2026.
This entry covers the full day of Monday 23 November 2026.

## How it works

`main.py` (Python 3.13, standard library only, no network) copies the
committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`
(falling back to `/output/entry.png`). The copy is byte-for-byte, so two
runs always produce identical output.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x9vj0gh6&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
