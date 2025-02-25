# Book Shelf
### List of books I read or plan to read on my quest to become the best technology developer in the world
Emphasized books were particularly useful.

### Books I have read :
#### Engineering

#### AI, ML and Data Science

| Feature      | ASLR      | KASLR      | KARL      |
| ------------- | ------------- | ------------- | ------------- |
| Randomization Scope | Randomizes memory regions of user-space processes (stack, heap, libraries, program code) | Randomizes only the base address of the kernel in memory | Randomizes only the base address of the kernel in memory | Fully relinks the kernel at boot, randomizing function and object placement |
| Affected Components | User-space programs and libraries  | Kernel base address (but function order remains the same) | Kernel functions, objects, and memory sections are randomly ordered |
| When it Happens | Every time a process is created or restarted | Only at boot time | Only at boot time, but generates a newly linked kernel each time |
| Effectiveness Against Attacks | Protects against user-space buffer overflow and ROP attacks | Helps prevent kernel exploits but does not fully prevent memory leaks from revealing kernel structure | Stronger than KASLR because function ordering changes per boot, making ROP-based attacks much harder |
| Predictability of Memory Layout | Changes for each process | Stays the same after boot, so if an attacker leaks an address, they can infer the rest | Even if an attacker leaks an address, the rest of the kernel layout remains unpredictable |
| Used In | Linux, Windows, MacOS, OpenBSD | Linux, Windows, macOS, OpenBSD  | OpenBSD only |



#### Mathematics

#### Cryptocurrencies, Blockchain and Quant Finance

### Books I Plan to Read:

#### Engineering

#### AI, ML and Data Science

#### Mathematics

#### Cryptocurrencies, Blockchain and Quant Finance
