# ration app
    

    installment_management
        ├── android/
        ├── ios/
        ├── lib/
            │   ├── core/
            │   │   ├── config/
            │   │   │   ├── app_config.dart
            │   │   │   └── environment.dart
            │   │   ├── constants/
            │   │   │   ├── app_constants.dart
            │   │   │   ├── assets_paths.dart
            │   │   │   └── strings.dart
            │   │   ├── errors/
            │   │   │   ├── exceptions.dart
            │   │   │   └── failure.dart
            │   │   ├── extensions/
            │   │   │   └── string_extensions.dart
            │   │   ├── network/
            │   │   │   ├── api_client.dart
            │   │   │   └── network_info.dart
            │   │   ├── services/
            │   │   │   ├── auth_service.dart
            │   │   │   ├── storage_service.dart
            │   │   │   └── logger_service.dart
            │   │   ├── utils/
            │   │   │   ├── date_utils.dart
            │   │   │   └── validators.dart
            │   │   └── widgets/
            │   │       ├── custom_button.dart
            │   │       └── loading_indicator.dart
            │   ├── features/
            │   │   ├── common/
            │   │   │   ├── models/
            │   │   │   │   └── address_model.dart
            │   │   │   └── widgets/
            │   │   │       └── shared_dropdown.dart
            │   │   ├── auth/
            │   │   ├── clients/
            │   │   │   ├── data/
            │   │   │   │   ├── datasources/
            │   │   │   │   │   ├── client_local_datasource.dart
            │   │   │   │   │   └── client_remote_datasource.dart
            │   │   │   │   ├── models/
            │   │   │   │   │   ├── client_model.dart
            │   │   │   │   │   └── mapper.dart
            │   │   │   │   └── repositories/
            │   │   │   │       └── client_repository_impl.dart
            │   │   │   ├── domain/
            │   │   │   │   ├── entities/
            │   │   │   │   │   └── client_entity.dart
            │   │   │   │   ├── repositories/
            │   │   │   │   │   └── client_repository.dart
            │   │   │   │   └── usecases/
            │   │   │   │       ├── add_client_usecase.dart
            │   │   │   │       ├── get_clients_usecase.dart
            │   │   │   │       ├── update_client_usecase.dart
            │   │   │   │       ├── delete_client_usecase.dart
            │   │   │   │       └── search_clients_usecase.dart
            │   │   │   ├── presentation/
            │   │   │   │   ├── bloc/
            │   │   │   │   │   ├── client_bloc.dart
            │   │   │   │   │   ├── client_event.dart
            │   │   │   │   │   └── client_state.dart
            │   │   │   │   ├── pages/
            │   │   │   │   │   ├── client_list_page.dart
            │   │   │   │   │   ├── client_details_page.dart
            │   │   │   │   │   ├── add_edit_client_page.dart
            │   │   │   │   │   └── client_onboarding_page.dart
            │   │   │   │   ├── widgets/
            │   │   │   │   │   ├── client_card.dart
            │   │   │   │   │   ├── client_form.dart
            │   │   │   │   │   └── client_error_widget.dart
            │   │   │   └── routes.dart
            │   │   ├── loans/
            │   │   ├── payments/
            │   │   ├── inventory/
            │   │   ├── expenses/
            │   │   ├── reports/
            │   │   ├── notifications/
            │   │   └── settings/
            │   ├── generated/
            │   │   └── json_serializable.g.dart
            │   ├── env/
            │   │   ├── dev.env
            │   │   └── prod.env
            │   ├── app.dart
            │   ├── injection_container.dart
            │   ├── main.dart
            │   └── routes.dart
            ├── test/
            │   ├── core/
            │   ├── features/
            │   │   ├── clients/
            │   ├── mocks/
            │   └── main_test.dart
            ├── assets/
            │   ├── images/
            │   ├── icons/
            │   └── fonts/
            ├── .gitignore
            ├── analysis_options.yaml
            ├── README.md
            └── pubspec.yaml
