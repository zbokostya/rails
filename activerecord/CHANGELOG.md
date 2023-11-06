*   Remove deprecated `TestFixtures.fixture_path`.

    *Rafael Mendonça França*

*   Remove deprecated behavior to support referring to a singular association by its plural name.

    *Rafael Mendonça França*

*   Deprecate `Rails.application.config.active_record.allow_deprecated_singular_associations_name`

    *Rafael Mendonça França*

*   Remove deprecated support to passing `SchemaMigration` and `InternalMetadata` classes as arguments to
    `ActiveRecord::MigrationContext`.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::Migration.check_pending` method.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::LogSubscriber.runtime` method.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::LogSubscriber.runtime=` method.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::LogSubscriber.reset_runtime` method.

    *Rafael Mendonça França*

*   Remove deprecated support to define `explain` in the connection adapter with 2 arguments.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::ActiveJobRequiredError`.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::Base.clear_active_connections!`.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::Base.clear_reloadable_connections!`.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::Base.clear_all_connections!`.

    *Rafael Mendonça França*

*   Remove deprecated `ActiveRecord::Base.flush_idle_connections!`.

    *Rafael Mendonça França*

*   Remove deprecated `name` argument from `ActiveRecord::Base.remove_connection`.

    *Rafael Mendonça França*

*   Remove deprecated support to call `alias_attribute` with non-existent attribute names.

    *Rafael Mendonça França*

*   Remove deprecated `Rails.application.config.active_record.suppress_multiple_database_warning`.

    *Rafael Mendonça França*

*   Ensure `#signed_id` outputs `url_safe` strings.

    *Jason Meller*

Please check [7-1-stable](https://github.com/rails/rails/blob/7-1-stable/activerecord/CHANGELOG.md) for previous changes.
