# Linux assignment

## 1. Excercise File

```bash
mkdir -p wipcamp12/{programmer,website,network,ux-ui}
cd wipcamp12
touch slide01.txt
cp slide01.txt slide02.txt
cp slide01.txt slide03.txt
cd
cp -R wipcamp12 wipcamp13
cd wipcamp13
rm slide03.txt
mv ../wipcamp12/slide01.txt newslide.txt
cd
rm -r wipcamp12 wipcamp13
```