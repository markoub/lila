# Lichess issue 20476 proof

Manual browser proof for `markoub/computer-color-setup-store`.

Flow:

1. Opened local lila at `http://localhost:9663/`.
2. Opened `Play against computer`.
3. Selected `Black`.
4. Closed and reopened the setup modal.
5. Confirmed `Black` remained selected and `lobby.setup.anon.ai` kept `"color":"black"`.

Artifacts:

- `before-close.png`
- `after-reopen.png`
- `proof.json`
