pipeline {
agent any
environment {
MY_GLOBAL_VARIABLE = 'value'
}
stages {
stage('Example') {
steps {
echo «Значение моей глобальной переменной: ${env.MY_GLOBAL_VARIABLE}»
}
}
}
}
