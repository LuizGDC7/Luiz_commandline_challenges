tar xzf challenges.tar.gz
cd challenges
ls
mkdir foo
mkdir -p foo/bar/1/2/3
rm -rf foo
echo "Hello World"
echo "Hello World" >> hello.txt
touch empty.txt
rm empty.txt
echo -n > empty.txt
cat > empty.txt
cp hello.txt goodbye.txt
mv goodbye.txt hello_copy.txt
diff hello.txt hello_copy.txt
cat hello.txt hello_copy.txt > 2_hellos.txt
pwd
ls -l
chmod 777 restricted.txt, echo "Meu nome é Luiz" > restricted.txt
./hello_executable
chmod 777 challenge_20, ./challenge_20
gcc compile_me.c -o compile_me && ./compile_me
./redirect &> output.txt
date
top
nproc
uname -r
grep -r "You found the needle in the haystack" bunch_of_files
head -25 people.csv
tail -25 people.csv
diff greeting1.txt greeting2.txt -U0
echo "Hello" && sleep 5 && echo "World"
printf '0%.0s' {1..1000000} > zero.txt
head -c 2000000 /dev/urandom > random.txt
wc -l README.txt
tac README.txt
cut -d ',' -f 2 people.csv
cut -d ',' -f 2 people.csv | sort | uniq | wc -l
Sim, contei
tail -n +2 people.csv | cut -d ',' -f 2 people.csv | sort | uniq | wc -l Porém awk -F ',' 'NR > 1 {print $2}' people.csv | sort | uniq | wc -l também funciona
time tail -n +2 people.csv | cut -d ',' -f 2 | sort | uniq | wc -l
time awk -F ',' 'NR > 1 {print $2}' people.csv | sort | uniq | wc -l
cut -d ',' -f 4 people.csv | grep Josiah | wc -l