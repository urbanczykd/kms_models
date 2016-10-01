## KmsModels

Requires at least PostgreSQL 9.2 because of JSON column type

## Installation

1. Add to Gemfile

        gem "kms_models"
        # or for edge version:
        gem "kms_models", github: "webgradus/kms_models"

2. Run generator:

        rails g kms_models:install

3. Copy migrations:

        rake kms_models:install:migrations

4. Migrate:

        bundle exec rake db:migrate

5. Recompile assets:

        bundle exec rake assets:precompile

6. Restart KMS instance