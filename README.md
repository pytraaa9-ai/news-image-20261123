# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/pytraaa9-ai/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/pytraaa9-ai/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

A program that writes one image summing up Monday 23 November 2026 world news — a newspaper front page (1024×1024 PNG): lead story Ukraine sinks the Russian corvette Merkury off Libya, second story Russian strikes kill 15 around Kyiv, plus 48 more stories across six continents, a world map, and Monday's market close with the Nvidia-led rebound. Full-day edition, v2 — 50 stories.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The day's news

- **Lead:** Ukraine sinks Russian corvette off Libya — Zelenskyy says seven sea drones sank the corvette Merkury at Benghazi on Sunday, hit cargo ship MV Angara and destroyed a Ka-27 helicopter. Satellite images show her capsized; Libya says only two drones hit.
- **Second story:** Russian strikes kill 15 around Kyiv — Dymer toll 11; boy Davyd, 7, and Valentyna, 79, pulled alive. Vyshneve 3 dead, Bila Tserkva 1; afternoon strike in central Kyiv injures 5.
- 153 drones overnight: Russia launches 153 drones; impacts at 11 sites; 2,471 troops lost in a day.
- Kerch Bridge crippled: Ukrainian strikes halt road traffic; only one rail track left open.
- Trilateral talks 'soon': Kremlin says a new Russia-US-Ukraine round is near, possibly in Abu Dhabi.
- Belgium strike chaos: National anti-austerity strike snarls transport; government fate in balance.
- Denmark: rapper murder plot: Russia accused of plotting to kill Ukrainian-American rapper Kyivstoner.
- Nuclear satellite feared: NATO intel: Russia plans to launch a satellite armed with a nuclear weapon.
- Sparta II hit in Baltic: Russian cargo ship catches fire in the Gulf of Finland after a drone strike.
- Kharkiv kindergarten hit: Russian drone strikes a kindergarten in Kharkiv; civilian sites in the firing line.
- Poland: three Kh-101 missiles: Prosecutors confirm three Russian cruise missiles found on Polish soil.
- Berlin aid up sixfold: Germany raises annual aid to Ukraine to nearly six times its 2022 level.
- 700,000 Russians dead: Meduza and Mediazona count 700,000+ Russian war dead by end of September.
- Istanbul rally: Thousands march against the crackdown on Turkey's opposition and media.
- Iran: 'all means' vs blockade: Tehran vows to use 'all available means' against the US naval blockade.
- Gaza: truck hit, 3 killed: Israeli forces hit a truck on Saturday; Oxfam warns 99% of Gaza is toxic.
- Eisenkot: 'Jewish terrorism': PM-elect condemns settler arson in Palestinian villages near Ramallah.
- Hodeidah telecom strike: Houthi media say a Saudi strike killed 17 at a telecom building; Riyadh silent.
- US sanctions Iran networks: Washington sanctions 20-plus targets in Iran's shadow banking network.
- UNRWA staffer killed: One UN staffer killed, three hurt in an Israeli attack in Gaza.
- Khartoum drones hit UN HQ: Drones from Ethiopia hit homes, the airport and a UN building; 3 killed.
- South Sudan: 24 civilians killed: Weekend attack in Tonj East kills 24, including 7 children.
- Banten fire: 24 dead: Candy-factory blaze toll confirmed; 30-34 still missing, 29 rescued.
- Korea: minister quits: Education chief resigns over AI cheating; first woman named spy chief.
- Hasina to be jailed if she returns: Dhaka: ex-PM faces arrest on return from India; death sentence stands.
- Thai MP: sentence cut to 3 years: Appeals court upholds royal-defamation conviction, halves the term.
- China: death for spy official: Ministry official sentenced to death for espionage; AI-chip spy ring.
- Chapo Isidro captured: Mexican military seizes Sinaloa cartel leader in a raid; 11 dead.
- Democrats win 258 House seats: Largest House majority in three decades; Trump curbs oversight.
- Vance won't say on Iran strikes: Vice-president declines to say if he would authorise strikes on Iran.
- ICE detain father, daughter: Masked agents seize pair on a Seattle jet bridge; passengers film it.
- Judge keeps ICE-shot man jailed: Court refuses to free Oscar Belgal, shot by ICE agents in October.
- Hubbard beats Foxx by 330: Recount confirms Democrat ousts 11-term Republican in North Carolina.
- Army to detonate Iowa chemicals: Army invokes emergency powers to blow up bomb chemicals on Wednesday.
- Court strikes down pregnancy law: Appeals court voids workplace accommodation law for pregnant women.
- Trump downplays FBI breach: President shrugs off the NCIC breach as the FBI opens a probe.
- Pentagon curbs Canada contact: Memo tells US troops to limit contact with Canadians; Ottawa has seen no memo.
- White House gags agencies: Counsel tells agencies: get approval before appearing before Congress.
- SpaceX sued over AI safety: Oregon and Virginia sue Musk's firm over AI-tool safety claims.
- UN AI weapons talks end: No binding rules on autonomous weapons; two years of talks agreed.
- Nvidia affair spy link: NYT: Jensen Huang's ex-lover kept contact with a Chinese spy official.
- SEC probing Nvidia accounts: Regulator scrutinises Nvidia's accounting practices, sources say.
- Huang back at Nvidia: Board reinstates Jensen Huang as CEO; shares surge 31.5%, best day since 2003.
- COP31: no deal, blame game: Guterres 'deeply disappointed'; EU and island states blame Saudi Arabia.
- Brazil storm hits town: Deadly storm hits a town; thousands forced from their homes.
- Paredes collapses on air: Argentina star collapses during a post-match interview in Colombia.
- Skubal: $450M Mets deal: Cy Young winner signs a nine-year, $450M deal, a record for a pitcher.
- Vanuatu quake 6.5, no tsunami: Magnitude 6.5 quake strikes the Vanuatu region; no tsunami threat.
- AI 'proves' Riemann?: Anthropic says AI helped prove the Riemann hypothesis; mathematicians debate it.
- NHS trials AI screening: Britain starts a major trial of AI in breast cancer screening.

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
