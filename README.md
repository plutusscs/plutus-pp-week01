# Plutus Pioneer Program - Week 01

The aim of these repositories is to give weekly snapshots of the Pioneer program (cohort 2)
but with all code working for the commit of the last week.

## Guidance

Information required to run the auction contract:

1. GetPOSIXTime  
import Ledger.TimeSlot
Ledger.TimeSlot.slotToPOSIXTime 10
POSIXTime {getPOSIXTime = 1596059101}

2. unCurrencySymbol - declared in myToken - use the hash  
show myToken  
"KnownCurrency {hash = 66, friendlyName = \"Token\", knownTokens = \"T\" :| []}"

See [the simulation](EnglishAuction.pdf)

## Note

These repositories serve also as test repositories for the hkvb/nixos.plutus image
that provides a containerised environment for the Playground and cabal repl
and comes with the accompanying Haddock documentation.
