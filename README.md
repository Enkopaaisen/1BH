# 1BPH

1 Button Power House (Turtle WoW version)

1. Druid feral dps functions
--IsMoonfireHit(), returns 1,0
--IsMoonfireDoTActive() returns 1,0
--noPounce(), returns true or nil, simple Pounce debuff check
--IsPounceImmune(), returns 1,0, using combatlog and checking immune warning
--PounceOpener(), returns 0 if failed, 1 if hit and not bleed immune
--PounceCount(), returns bleed ticks
--IsPounceDoTActive(), returns 1, 0, more accurate way of tracking Pounce debuff from player
--noRake(), returns true or nil, simple Rake debuff check
--IsRakeImmune(), returns 1,0, using combatlog and checking immune warning
--IsRakeHit(), returns 0 if failed, 1 if hit 
--RakeCount(), returns bleed ticks
--IsRakeDoTActive(), returns 1, 0, more accurate way of tracking Rake debuff from player
--noRip(), returns true or nil, simple Rip debuff check
--IsRipImmune(), returns 1,0, using combatlog and checking immune warning
--RipOpener(), returns 0 if failed, 1 if hit and not bleed immune
--RipCount(), returns bleed ticks
--IsRipDoTActive(), returns 1, 0, more accurate way of tracking Rip debuff from player
-- returns elapsed, remaining = GetTimerStatus()
-- resets with ResetTimer()
--IsBehindCheck(), returns 0,1 checking if player is from behind
--IsSwingCheck(), returns 0,1 checking if player is swimming
--NextEnergyTick(), returns time to next energy tick in cat form, used for timing check when powershifting
--GetCatFormManaCost(), returns mana cost for cat form, used for mana check when poweshifting
--GetClawBonusDamage(), returns claw dmg bonus from tooltip, used for dmg, hp check during rotation
--GetRavageBonusDamage(), returns ravage dmg bonus from tooltip, used for dmg, hp check during rotation
--PlayerDmg(), returns avg player dmg from stats panel, used for dmg caculation for cat abilities
--PlayerAP(), returns avg player dmg from stats panel, used for dmg caculation for cat abilities
--noWild(), returns true, false for checking MOTW buff
--noTho(), returns true, false for checking Thorns buff
--noMoon(), returns true, false for checking moonfire dot
--noTrF(), returns true, false for checking if in travel form
--noAQ(), returns true, false for checking if in aquatic form
--noCF(), returns true, false for checking if in cat form
--noBF(),returns true, false for checking if in bare form
--noDR(),returns true, false for checking debuff Demoralizing Roar
--noTF(),returns true, false for checking buff tigers fury
--noBloodFrenzy(),returns true, false for checking buff blood frenzy
--noFF(), retruns true, false for checking debuff Faerie Fire
--ST(),returns true, false for checking if is stealth
--noOOC(),returns true, false for checking buff omen
--noInnervate(),returns true, false for checking buff innervate
--InnervateCD(), returns Innervate CD, Spell needs to be in actionbar slot, right now it is in slot 15(can be changed)
--DotImmuneByType(), listed elemental and mechanical type for bleed immune, needs to be maintained and revised
--BleedImmuneByList(), mob list, needs to be maintained and revised
--DotImmune(), sum up for bleed immune
--FFImmune(), listed elemental and mechanical type for Faerie Fire immune, needs to be maintained and revised
--LvlCheck(), player lvl- target lvl for dmg check
--PowerShift(), also shows mana remaing and will try to stop cast cat form if mana is too low
----------------------------------------------------------------------------------------------------------------------------------------------------
--examples are all spammable macros, it is recomanded to spam the button!!!
--CasterAttack(), casts wrath, moonfire and melee attack in casterform
--TravelForm(), casts travel form or aquatic form
--CatForm(), casts cat form and checking for mana
--BearForm(), casts bear form 
--PSClaw(), casts claw with powershift if needed
--PSRake(), casts rake with powershift if needed
--PSRip(), casts rip with powershift if needed
--PSTF(), casts tigersfury with powershift if needed
--CastFinshFB(), casts Ferocious Bite with powershift if needed
--CatSimple(party,spell,sec,e,f), party no, spell, sec to death, e cat dps, f Rake dot an example of cat rotation
--BearAttack(spell), spell: maul or swipe.
--DruidAttack(bearspell, cparty,cspell,csec,ce,cf), maul/swipe, party no, spell, sec to death, e cat dps. sum up a feral rotation depending cat or bear form








