# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/v1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [2.1.0] - 2019-09-12
-  Custom IAM role

## [2.0.0] - 2019-09-12
### Changed
-   Terraform 0.12 support
-   Refactoring list resources function

## [1.9.0] - 2019-08-09
### Added
-   Force utf-8 encoding

### Changed
-   Refactoring whole Python code
-   Set Flake8 max-complexity to 10 instead of 20
-   Change waiting delay in integration tests

## [1.8.0] - 2019-08-03
### Added
-   Test Python code with Tox
-   Test Python code with travis-ci
-   Test Terraform code with terraform fmt command

### Changed
-   Flake8 codestyle convention
-   Black formating
-   Pylint refactoring

## [1.7.2] - 2019-07-10
### Changed
-   Don't shutdown all instances when no autoscaling group is found

## [1.7.1] - 2019-06-30
### Added
-   Tests for spot instance scheduler
-   Parallel testing with Terratest

### Changed
-   Update test directory structure

## [1.7.0] - 2019-06-30
### Added
-   Spot instance support
-   Terratest tests for ec2 shceduler
-   Terratest tests for autoscaling scheduler

### Changed
-  Update README.md

### Removed
-   Remove Gemfile

## [1.6.1] - 2019-06-21
### Added
-   Ouputs in Terraform examples

### Changed
-   Lambda outputs name

## [1.6.0] - 2019-06-20
### Added
-   Enable Lambda Cloudwatch logs

### Changed
-   Improve Python exception handler
-   Improve Terraform rds example
-   Linting Python main.py

## [1.5.0] - 2019-05-31
### Changed
-   Power-off instances instead of terminating with autoscaling scheduler
-   Use aws region eu-west-1 with Terraform examples

## [1.4.3] - 2019-05-09
### Changed
-   Update awspec tests
-   Update version in Gemfile

## [v1.4.2] - 2019-05-04
### Added
-   Use travis-ci pipeline

## [v1.4.1] - 2019-04-05
### Changed
-   Add boto3 paginator for autoscaling and rds function
-   Improve Terraform examples

## [v1.4.0] - 2019-04-02
### Added
-   Add more aws examples

### Changed
-   Split python code into multiple file
-   Refactoring python code
-   Fix autoscaling deletion

## [v1.3.0] - 2019-02-23
### Added
-   Add python log output for every resources stop and start

### Changed
-   Fix tag filter for instances start and stop

## [v1.2.2] - 2019-02-19
### Added
-   Improve comments

### Changed
-   Lint code

## [v1.2.1] - 2019-02-10
### Changed
-   When autoscaling shceduler is set to stop, terminate all instances in it

## [v1.2.0] - 2019-02-09
### Added
-   kitchen-ci with awspec test
-   Test fixture example

## [v1.1.0] - 2019-02-07
### Added
-   Autoscaling support with scheduler

## [v1.0.0] - 2019-02-05
### Added
-   ec2 instances support with scheduler
-   rds instances support with scheduler
-   rds clusters support with scheduler


[Unreleased]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.9.0...HEAD
[1.9.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.8.0...1.9.0
[1.8.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.7.2...1.8.0
[1.7.2]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.7.1...1.7.2
[1.7.1]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.7.0...1.7.1
[1.7.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.6.1...1.7.0
[1.6.1]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.6.0...1.6.1
[1.6.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.5.0...1.6.0
[1.5.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/1.4.3...1.5.0
[1.4.3]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.4.2...1.4.3
[v1.4.2]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.4.1...v1.4.2
[v1.4.1]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.4.0...v1.4.1
[v1.4.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.3.0...v1.4.0
[v1.3.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.2.2...v1.3.0
[v1.2.2]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.2.1...v1.2.2
[v1.2.1]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/diodonfrost/terraform-aws-lambda-scheduler-stop-start/releases/tag/v1.0.0
