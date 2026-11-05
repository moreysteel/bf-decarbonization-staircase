# Blast furnace decarbonization staircase

A self-contained, interactive view of the results of a physics-based blast furnace decarbonization model: cost against CO₂ for twelve injection cases on one sample furnace, with price sliders, the capital checklist, the cost build-up, charging, furnace, raceway and gas-balance views, and a "Your furnace" form for checking and pricing your own base period.

Open the page: https://moreysteel.github.io/bf-decarbonization-staircase/

Joe Morey · Morey Industrial Consulting, LLC · results from a model under active development, shared for discussion. The page carries the solved results and the cost arithmetic; the furnace model itself is not in this repository.

## Collaborators' copy (passphrase-gated)
`collab/index.html` is the same page, gzip-compressed and AES-256-GCM-encrypted under a passphrase (PBKDF2-HMAC-SHA256, 600 000 rounds), decrypted in the visitor's browser. The hosted file is ciphertext; the link shows nothing without the passphrase, which is sent to collaborators separately. Comments made from that copy go to the owner by e-mail (no account needed). Built by `stair/page/build_gate.py` in the model package.
