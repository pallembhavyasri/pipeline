// pipeline{
//     agent any
// parameters {
    //     string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    //     text(name: 'BIOGRAPHY', defaultValue: '', description: 'Enter some information about the person')
    //     booleanParam(name: 'TOGGLE', defaultValue: true, description: 'Toggle this value')
    //     choice(name: 'CHOICE', choices: ['One', 'Two', 'Three'], description: 'Pick something')
    //     password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter a password')
    // }
properties([
    parameters([
        string(name: 'TARGET_ENV', defaultValue: 'staging', description: 'Deployment environment')
    ])
])
node{
            stage("Bulid"){
                steps{
                    echo "This is bulid stage"
                }
            }
            stage("Test"){
                steps{
                    echo "This is test stage"
                }
            }
            stage("Deploy"){
                steps{
                    echo "this is Deploy"
                }
            }
            stage("Params accessing"){
                steps{
                    echo "name is ${params.TARGET_ENV}"
                }
            }
        }
