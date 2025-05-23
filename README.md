git checkout -b feature-greeting
echo "This is a new feature." > feature.txt
git add feature.txt
git commit -m "Add feature description"
echo -e "This is the description of my repo\nModification in feature-greeting branch." > README.md
git add README.md
git commit -m "Modify README in feature-greeting branch"
git push origin feature-greeting
git checkout main
echo -e "This is the description of my repo\nModification in main branch." > README.md
git add README.md
git commit -m "Modify README in main branch"
