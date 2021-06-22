# CMake Conan template

with the help of this script, create CMake supported conan template empty structure.

#### Usage
```powershell
$ python run.py --help
usage: run.py [-h] [--project_name PROJECT_NAME] [--empty_project {0,1}]

CMake-Conan-template-creator

optional arguments:
  -h, --help            show this help message and exit
  --project_name PROJECT_NAME
                        Enter project name
  --empty_project {0,1}
                        Create empty project structure, ({0} - conan CMake app
                        structure), ({1} - conan CMake lib structure)
                        
```

**To create CMake conan application structure [python script]**
```powershell 
python run.py --project_name=sampleApplication --empty_project=0
```

**To create CMake conan library structure [python script]**
```powershell
python run.py --project_name=sampleLibrary --empty_project=1
```

### Bug report

if you face any issue or need any kind of other help. Please raise a issue.

### Contributing

Please read the [CONTRIBUTING](https://github.com/shajeen/CMake-Conan-template-creator/blob/main/CONTRIBUTING.md) before raising the PR.
