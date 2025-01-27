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