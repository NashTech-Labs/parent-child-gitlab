# Parent-Child Gitlab Pipeline Templates

## Usage

1. Simply clone repo 

```
git clone https://github.com/knoldus/parent-child-gitlab.git
cd parent-child-gitlab
```

2. Copy files into your Project repo

```
mkdir -p $PROJECT_REPO/.gitlab/workflows
cp .gitlab-ci.yml $PROJECT_REPO/
cp -r .gitlab $PROJECT_REPO/
```

3. Add your scripts & variables for your project needs.