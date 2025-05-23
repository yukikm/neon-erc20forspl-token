# Neon Bootcamp Week1

## Beginner task

- I created YUKI token.
  [code](https://github.com/yukikm/neon-erc20forspl-token/blob/05d4d7ca0b67604ca7f041a519be2e600f8d6f4e/scripts/TestCallSolana/TestDevBootcamp.js#L34-L40)

```
// Deploy ERC20ForSplMintable contract
  tx = await ERC20ForSplFactory.createErc20ForSplMintable(
    "0xyuki token " + Date.now().toString(),
    "YUKI",
    9,
    user1.address
  );
  await tx.wait(1);
```

- [Token address(Neon Devnet Explorer)](https://neon-devnet.blockscout.com/address/0x9B3E78036871D1359F48bAa5Bbe15Bc933f95f97)
- [Token address(SOLSCAN Devnet Explorer)](https://solscan.io/token/64VW1YpT24KmRke5c9nnRGMyRqpf9ECUsoK1nJu5QZuo?cluster=devnet#metadata)

## Intermediate task

- I try to transfer token by using ICallSolana. [code](https://github.com/yukikm/neon-erc20forspl-token/blob/05d4d7ca0b67604ca7f041a519be2e600f8d6f4e/scripts/TestCallSolana/TestDevBootcamp.js#L112-L117)
- [Deployed contract(Neon Devnet Explorer)](https://neon-devnet.blockscout.com/address/0x70B3dDE39013cB8A54fcAE026e043aCcdb334F41)
- [Transfer transaction(Neon Devnet Explorer)](https://neon-devnet.blockscout.com/tx/0x787b686d05995d8695d068af6cc96efc2db12089d421c04734a9f1cf5308eeb2)
- [Transfer transaction(SOLSCAN Devnet Explorer)](https://solscan.io/tx/xqyt6UsBTnrcHmV2Yt8jeC3tticeaEFu7LSMN6Ber7YD8qsNrxU1G7EZspuvZgd7mTWPpKKEP89s2NfPuV8JAhb?cluster=devnet)
