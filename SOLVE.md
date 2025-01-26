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