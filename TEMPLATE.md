TEMPLATE
___

# Clone Repository

```bash
cp -pr flex-skeleton-bundle flex-{name}-bundle
cd flex-{name}-bundle
rm .git -Rf
git init
git add .
```
# Move Files

```bash
mv src/FlexPHPSkeletonBundle.php src/FlexPHP{Name}Bundle.php
mv src/DependencyInjection/FlexPHPSkeletonExtension.php src/DependencyInjection/FlexPHP{Name}Extension.php
```

# Replace Names

```bash
grep -rls "skeleton" | xargs sed -i 's/skeleton/{name}/g'
grep -rls "Skeleton" | xargs sed -i 's/Skeleton/{Name}/g'

# or

vim
e README.md
%s#skeleton#{name}#g
%s#Skeleton#{Name}#g

e composer.json
%s#skeleton#{name}#g
%s#Skeleton#{Name}#g

e config/services.xml
%s#skeleton#{name}#g
%s#Skeleton#{Name}#g

e config/routes.xml
%s#skeleton#{name}#g
%s#Skeleton#{Name}#g

e src/DependencyInjection/ConfigSchema.php
%s#skeleton#{name}#g
%s#Skeleton#{Name}#g

e src/FlexPHP{Name}Bundle.php
%s#Skeleton#{Name}#g

e src/DependencyInjection/FlexPHP{Name}Extension.php
%s#Skeleton#{Name}#g
```

# Commiting

```bash
git add .
git commit -m "Initial commit"
```

# Branching

```bash
git flow init -d
```

# Using this script

```bash
s#{name}##g
s#{Name}##g
```

