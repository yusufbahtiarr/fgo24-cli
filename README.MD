# Mini-task CLI Usage

This is bare minimum usage of cli, according to mini task on **Day 1** (14/04/2025)

## Without loop (CMD)

```cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
"" > latihan1.txt
"" > latihan2.txt
"" > latihan3.txt
"" > latihan4.txt
"" > latihan5.txt
dir
rmdir latihan4.txt
mkdir latihan4.txt
rmdir latihan5.txt
mkdir latihan5.txt
dir
rmdir latihan4.txt
```

## With loop (CMD)

```cmd
mkdir "Latihan CLI Dasar"
cd "Latihan CLI Dasar"
for /l %i in (1,1,5) do copy nul > latihan%i.txt
dir
del "latihan4.txt"
mkdir "latihan4.txt"
del "latihan5.txt"
mkdir "latihan5.txt"
dir
rmdir "latihan4.txt"
```

## Memindahkan Lagu (CMD)

```cmd
for %i in (Blackpink, Evanescence, "Linkin Park") do mkdir %i
for %i in (Blackpink, Evanescence, "Linkin Park") do move %i*.mp3 .\%i
```
