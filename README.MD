# Mini-task CLI Usage

This is bare minimum usage of cli, according to mini task on **Day 1** (14/04/2025)

## Without loop

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

## With loop

```cmd
cd lagu
for %i in (Blackpink, Evanescence, "Linkin Park") do mkdir %i
for %i in (Blackpink, Evanescence, "Linkin Park") do move %i*.mp3 .\%i
```

## This New

1. This
2. Is
3. A
4. New
