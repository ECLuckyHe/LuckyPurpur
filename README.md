# LuckyPurpur

1. Install Gradle.
2. Install Java 17.
3. Run commands.

```shell
git clone https://github.com/ECLuckyHe/LuckyPurpur.git
git clone https://github.com/PurpurMC/Purpur.git
cd Purpur
git reset --hard 2a38801aebc54ea0c9bf4825ca1f6e66b2bd7f03
cp ../LuckyPurpur/patches/server/* ./patches/server/
gradle createReobfPaperclipJar
```