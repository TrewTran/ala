# ala
git clone <url-repo>
cd <folder>
for i in {1..25}
do
  echo "commit $i" >> log.txt
  git add .
  git commit -m "commit $i"
done

