load("@tf_modules//rules:terraform.bzl", "terraform_working_directory")

terraform_working_directory(
    name = "terraform",
    module = "//examples/provider:provider",
    providers = [
        "//examples/provider/example_provider:provider_examplecorp_example",
        "@provider_hashicorp_local//:provider",
    ],
)
