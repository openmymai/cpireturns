## Solana Development using Anchor

Anchor is a Rust framework that facilitates the creation of dApps on the Solana blockchain.
One of the peculiarities of developing on Solana is the need to use a lot of template code, 
which can be a rather time-consuming and costly process. Anchor makes this process much easier and 
reduces development time by providing various tools such as (de)serialization of accounts and instruction data.

### Anchor Program
Let's consider them in a test case from the developers of the Anchor framework, 
namely a simple decentralized application that makes cross-program invocations (CPI). 

```
anchor init cpi-returns
cd cpi-returns
anchor build
```

> In my case, there is an error so I fix it by changing "version = 4" to "version = 3" in Cargo.lock file

<img width="956" alt="Screenshot 2025-01-18 at 11 08 40 AM" src="https://github.com/user-attachments/assets/4fbcc37a-f181-4681-95d4-73924780a7d7" />


