example
=
```
#!/bin/bash
echo "hello world"
```
example
=
```
#!/bin/bash
# promt the user for credentials

read -p 'username: ' username
read -sp 'password: ' password

echo "thank, your creds are as follow: " $username " and &password
```

example if
=
```
#!/bin/bash
# if statement

read -p "what is your age: " age

if [ $age -lt 16 ]
then
  echo "you might need parental permission to take this course!"
fi
```

example else if
=
```
#!/bin/bash
# else if statement
read -p "what is your age: " age

if [ $age -lt 16 ]
then
  echo "you might need parental permission to take this course!"
else
  echo "welcome to the coruse!"
fi
``

example else if elif
=
```
#!/bin/bash
# else if statement
read -p "what is your age: " age

if [ $age -lt 16 ]
then
  echo "you might need parental permission to take this course!"
elif [ $age -gt 60 ] 
then 
  echo "hats off to you, respect!"
else
  echo "welcome to the coruse!"
fi
``

example
=
```
#!/bin/bash
if [ $USER =='ice'] && [$HOSTNAME='ice']
then
  echo "Mutiple statements are true!"
else
  echo "not miush to see here ..."
fi
```










