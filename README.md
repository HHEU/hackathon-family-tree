# hackathon-family-tree
Tracing the lineage of the EU hackathon scene! 

![Mermaid generated graph](https://cloud.githubusercontent.com/assets/1790822/22543983/4982a21e-e933-11e6-9bd2-59757d5518c9.png)

If you think you know where a hackathon lives in this tree, or you see an error, please create a pull request. 

Whilst we go through data discovery, this will initially be an awful list of lists. There may be repeated data as nested lists don't express multiple-parents very well. 

Below is the starting of a [Mermaid](https://knsv.github.io/mermaid/) graph.

# The Yahoo! Hack Dynasty

- Yahoo! Hack
  - Over The Air
  - CharityHack (also parented by BarCamp)
    - BattleHack
  - LeedsHack
    - HackManchester
      - Hack24
        - LincolnHack
        - HackTheMidlands
  - Hacked.io (also parented by Mashed 2008)
    - Hackference (also parented by Kings of Code)
      - BanterHack
      - BrumHack (The Jack and Lily Generation)
      - HackNotts
        - AnvilHack
          - Sex Tech Hack
        - Launch Hack (also parented by StudentHack)
          - DragonHacks
          - HackNE
          - Landing Hack
          - WarwickHACK
            - CUCC Hack
          - Hack the Holidays
          - Hack the Burgh
          - StacsHack
            - StirHack
            - StrathHack
            - HackDee
            - RGU Hack

# PennApps Dynasty

- PennApps
  - KairosHacks
    - HackUPC
  - HackCambridge
  - AGHacks (also parented by MHacks)
  
# House of the Civic Hackathons 
### (Otherwise known as "Kevin's Fault")

- National Hack the Government
  - Young Rewired State
    - BrumHack (Poppie)
      - Aston Hack 
      - HackTheMidlands (also parented by Hack24)
    - RU Hacking
  - Parly Hack
      - Accountability Hack
  - UKGovHack
 
# Fallen Angels

- AngelHack
  - jacobsHack!
    - CopenHacks
    - LauzHack
    - OxfordHack
    - DO!Hack

# Orphaned Houses

- StudentHack
  - Launch Hack
  - GreatUniHack
- HackKings
  - HackLondon
    - Porticode (also parented by NYC Unhackathon)
    - HackCity
  - HackCortona
- ICHack
- JP Morgan Code For Good
  - DurHack
- HackaSoton
    - HackTrain
    
# Mermaid Graph
[View the graph](http://bit.ly/hheutree)  
[Edit the graph](http://bit.ly/hheutreeedit)

graph TD;  
    Yahoo!Hack-->CharityHack;  
    Yahoo!Hack-->LeedsHack;  
    Yahoo!Hack-->Hacked.io;  
    Yahoo!Hack-->OverTheAir;  
    Mashed2008-->Hacked.io;  
    CharityHack-->BattleHack;  
    Hacked.io-->Hackference;  
    KingsOfCode-->Hackference  
    LeedsHack-->HackManchester;  
    HackManchester-->Hack24;  
    Hack24-->LincolnHack;  
    Hack24-->HackTheMidlands;  
    Hackedference-->BanterHack;  
    Hackference-->BrumHack;  
    Hackference-->HackNotts;  
    HackNotts-->AnvilHack;  
    AnvilHack-->SexTechHack;  
    HackNotts-->LaunchHack;  
    StudentHack-->LaunchHack;  
    LaunchHack-->DragonHacks;  
    LaunchHack-->HackNE;  
    LaunchHack-->LandingHack;  
    LaunchHack-->WarwickHACK;  
    WarwickHACK-->CUCCHack;  
    LaunchHack-->HackTheHolidays;  
    LaunchHack-->HackTheBurgh;  
    LaunchHack-->StacsHack;  
    StacsHack-->StirHack;  
    StacsHack-->StrathHack;  
    StacsHack-->HackDee;  
    StacsHack-->RGUHack;  
    PennApps-->KairosHacks;  
    KairosHacks-->HackUPC;  
    PennApps-->HackCambridge;  
    PennApps-->AGHacks;  
    MHacks-->AGHacks;  
    NationalHackTheGovernment-->YoungRewiredState;  
    YoungRewiredState-->BrumHack;  
    YoungRewiredState-->RUHacking;    
    BrumHack-->AstonHack;  
    BrumHack-->HackTheMidlands;  
    NationalHackTheGovernment-->ParlyHack;  
    NationalHackTheGovernment-->UKGovHack;  
    AngelHack-->jacobsHack!;  
    jacobsHack!-->CopenHacks;  
    jacobsHack!-->LauzHack;  
    jacobsHack!-->OxfordHack;  
    jacobsHack!-->DO!Hack;  
    StudentHack-->GreatUniHack;  
    HackKings-->HackLondon;  
    HackKings-->HackCortona;  
    HackLondon-->Porticode;  
    HackLondon-->HackCity;  
    ICHack;  
    JPMCodeForGood-->DurHack;  
    HackaSoton-->HackTrain;  
