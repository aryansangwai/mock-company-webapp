pipeline {
 name: Jenkins Simulation

on: [push, pull_request]

jobs:
  jenkinsfile:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Run Jenkinsfile Runner
        uses: Jenkins/jenkinsfile-runner-action@v1

}
