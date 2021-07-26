# Intro-to-Cybersecurity

## Common Terms

CIA (Confidentiality, Integrity, Availability) Triad
![CIA_Triad](https://user-images.githubusercontent.com/79841341/126899291-d8a9110d-1ef8-4eea-89bf-d51c673fa714.png)

## Lab 1:
- Reinstall WSL2 and Ubuntu
- Reinstall docker
  - sudo needs to be run with docker
- flag:
  - Location:

    ```bash
    root@94e4ddaed551:/# find / -iname 'flag.txt' -type f
    /root/flag.txt
    root@94e4ddaed551:/# cat $(find / -iname 'flag.txt' -type f)
    CITS1003{y0u_f0und_7h3_f1r57_fl46}
    ```
    
    
