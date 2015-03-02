# Boston Key Party CTF 2015: Museum Of Fine Arts

**Category:** School-Bus
**Points:** 25
**Solves** 
**Description:**

> Because cryptography is hard, we only implemented a hand-made PRNG. What could possibly go wrong? : 25

## Write-up

we don't really need to predict any seeds as it looks
it's comparing the entered password with the one in the session
so before you fill in the session call it

curl http://52.10.107.64:8004/?password=

## Other write-ups and resources

* none yet
