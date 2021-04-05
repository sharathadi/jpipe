pipeline {
 agent any
  stages {
 stage('BUILD') {
steps {
 sh '''
#!/bin/bash
echo "check 1"

git clone https://github.com/sharathadi/cprgm.git

make
  '''
}
}
}
}
