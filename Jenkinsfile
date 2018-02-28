node {
  // Checkout code from repository and update any submodules
  stage ("Checkout") {
    echo "Checkout"
  }

  stage ("Build") {
    echo "Current branch is ${env.BRANCH_NAME}."
    echo "Current description is ${commitDescription}."
  }


  stage ("GitHub Release") {
    echo "Skipped."
  }
}
