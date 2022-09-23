## Lab 04

- Name: Donnell Smith
- Email: smith.2883@wright.edu

## Part 1 Answers

1. grep -E -o 'x[0-9]{4}' grepdata.txt -i
2. grep -E
3. grep -E "20[0-9]{3}" grepdata.txt
4. grep -E "CA" grepdata.txt -i
5. grep -E "@" grepdata.txt -n

## Part 2 Answers

1. sed -i 's/<html>/<stuff>/g' sedfile.html > sedfile.md
2. sed -i 's/<li>/-""/g' sedfile.html > sedfile.md
3. sed -i 's/<h1>/#""/g' sedfile.html > sedfile.md
4. sed -i 's/<h2>/##""/g' sedfile.html > sedfile.md
5. sed -i 's/<u1>/g' sedfile.html > sedfile.md 
   sed -i 's/<html>/""/g' sedfile.html > sedfile.md
6. sed -i 's/Batches/Matches/g' sedfile.html > sedfile.md

## Part 3 Answers

1. awk '/Bil/ {print $1}' records.txt
2. awk '$4 == 42 {print $4}' records.txt
3. awk '/wright.edu/ {print $2, $1, $3}' records.txt
4. awk '/wright.edu/, $6 == 1234 {print $2, "Favorite number is", $4}' records.txt
5. awk '{gsub("space.edu","universe.edu", $3); print $0}' records.txt > update1.txt
6. awk '{gsub("$6","NOT@PL@!NP@SSWORD", $6); print $0}' records.txt > update2.txt

## Part 3 Answers
