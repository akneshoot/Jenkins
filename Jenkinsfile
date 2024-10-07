pipeline {
agent any
stages {
stage(“Build”) {
steps {
echo “Building…”
// Шаги сборки
}
}
stage(“Test”) {
steps {
echo “Testing…”
// Шаги тестирования
}
}
stage(“Deploy to Staging”) {
steps {
echo “Deploying to Staging…”
// Шаги развертывания на стейджинг
sh “./deploy staging”
}
}
stage(Deploy to Production') {
steps {
echo “Deploying to Production…”
// Шаги развертывания на продакшн
sh “./deploy production”
}
}
}
