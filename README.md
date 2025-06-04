# Password Manager App🔒🔑.

Welcome to the Password Manager App, a secure solution built using Flutter to help you manage your passwords securely and effortlessly.

![324192795-b8ec26af-4c8d-4604-a168-07a7745ba046](https://github.com/user-attachments/assets/c5e0854f-67bb-485f-a3d6-45b06c0b3bf4)


## ⚙ Tools Used
- Flutter 
- Dart
- Firebase
- FastLane
- GitHub Actions

## ✨ Features
✔ Beautiful UI.\
✔ Code written by Clean Architecture paradigm.\
✔ CI/CD Firebase App Distribution.\
✔ CI/CD FastLane.\
✔ CI/CD GitHub Actions.\
✔ Sign in with Email and Password.\
✔ Sign in with Facebook.\
✔ Sign in with Google.\
✔ Firebase Realtime Database.\
✔ Password Analysis.

# Screenshots
## Light Mode

  Splash Page                 |   Login Page        |  Sign up Page
:-------------------------:|:-------------------------:|:-------------------------:
![Splash Screen](https://github.com/user-attachments/assets/abdc12e7-6eaf-4ae2-b2fe-641e1d39ff8c)|![Login](https://github.com/user-attachments/assets/767d804e-5404-424b-8edf-6a4b29b24992)|![Sign up](https://github.com/user-attachments/assets/1c35c1bd-e606-4aa0-8889-867eff1f47a6)


  Home Page                 |   Security Analysis 1 Page        |  Security Analysis 2 Page
:-------------------------:|:-------------------------:|:-------------------------:
![Home Screen](https://github.com/user-attachments/assets/cb604adc-9c6f-404f-827b-ba1d662cd82d)|![Security Analysis 1 ](https://github.com/user-attachments/assets/030f28d0-2dad-42fb-b349-9e9ae0da5aa2)|![Security Analysis 2](https://github.com/user-attachments/assets/2c15a20c-f721-448f-ad7b-6ba722bedede)



  Add New Password 1 Page                 |   Add New Password 2 Page        |  Settings Page
:-------------------------:|:-------------------------:|:-------------------------:
![Add New Password 1](https://github.com/user-attachments/assets/645dcf49-89a6-427c-8538-25e8a7190a42)|![Add New Password 2](https://github.com/user-attachments/assets/a5c6b807-dcb3-428f-be9c-4c65f537c6bc)|![Settings](https://github.com/user-attachments/assets/a1449635-576f-43e9-a586-9240c98b4ffb)


  Profile Screen Page                 |   Edit Profile Page        |  Forgot Password Page
:-------------------------:|:-------------------------:|:-------------------------:
![Profile Screen](https://github.com/user-attachments/assets/7461c5be-a8d8-40cc-854f-7ab549a2ac1f)|![Edit Profile ](https://github.com/user-attachments/assets/987e1c41-7a79-42a6-8346-c39f0d9eb4fb)|![Forgot Password ](https://github.com/user-attachments/assets/09f95704-0e87-472e-ab6f-1b1e29d10e41)



## Directory Structure

```
lib
│
├── core/
│   ├── base/
│   │   ├── api/
│   │   │   └── end_points.dart
│   │   ├── base_export.dart
│   │   ├── bloc_observer.dart
│   │   └── service_locator.dart
│   ├── core_export.dart
│   ├── l10n/
│   │   ├── app_ar.arb
│   │   ├── app_en.arb
│   │   └── language_manager.dart
│   ├── models/
│   │   ├── enums/
│   │   │   ├── app_supported_languages_enum.dart
│   │   │   ├── app_them_mode_enum.dart
│   │   │   ├── image_type.dart
│   │   │   └── toast_type.dart
│   │   ├── firebase/
│   │   │   └── search_model.dart
│   │   └── models_export.dart
│   ├── services/
│   │   ├── cache/
│   │   │   └── app_prefs.dart
│   │   ├── responsive_design/
│   │   │   └── responsive.dart
│   │   └── services_eport.dart
│   └── utils/
│       ├── app_utils.dart
│       ├── extensions/
│       │   ├── extensions_export.dart
│       │   ├── language.dart
│       │   └── strings.dart
│       ├── image_utils.dart
│       ├── routes/
│       │   ├── router.dart
│       │   ├── routes.dart
│       │   └── routes_export.dart
│       ├── theme/
│       │   ├── app_colors.dart
│       │   ├── app_fonts.dart
│       │   ├── app_sizes.dart
│       │   ├── app_styles.dart
│       │   ├── app_theme.dart
│       │   ├── cubit/
│       │   │   ├── theme_cubit.dart
│       │   │   └── theme_state.dart
│       │   ├── font_weight_helper.dart
│       │   ├── image_assets.dart
│       │   └── theme_export.dart
│       ├── utils_epxort.dart
│       └── validators/
│           ├── confirm_password_validator.dart
│           ├── custom_validator.dart
│           ├── email_validator.dart
│           ├── length_validator.dart
│           ├── min_length_validator.dart
│           ├── multi_validator.dart
│           ├── name_validator.dart
│           ├── number_validator.dart
│           ├── password_validator.dart
│           ├── url_validator.dart
│           ├── validate_messages.dart
│           ├── validators.dart
│           └── validator_export.dart
├── features/
│   ├── features_export.dart
│   ├── home/
│   │   ├── const/
│   │   │   └── home_const.dart
│   │   ├── home_export.dart
│   │   ├── models/
│   │   │   └── bottom_navigation_item_model.dart
│   │   └── presentation/
│   │       ├── cubit/
│   │       │   ├── home_cubit.dart
│   │       │   └── home_state.dart
│   │       ├── pages/
│   │       │   ├── home_page.dart
│   │       │   └── web_browser.dart
│   │       └── widgets/
│   │           ├── home_bottom_nav_bar.dart
│   │           └── password_vault_widget.dart
│   ├── login/
│   │   ├── data/
│   │   │   ├── datasources/
│   │   │   │   └── login_remote_datasource.dart
│   │   │   ├── enum/
│   │   │   │   └── firebase_auth_type.dart
│   │   │   ├── models/
│   │   │   │   ├── additional_user_info_profile_model.dart
│   │   │   │   └── log_model.dart
│   │   │   └── repositories/
│   │   │       └── login_repo_impl.dart
│   │   ├── domain/
│   │   │   ├── repositories/
│   │   │   │   └── login_repo.dart
│   │   │   └── usecases/
│   │   │       └── login_usecase.dart
│   │   ├── login_export.dart
│   │   └── presentation/
│   │       ├── cubit/
│   │       │   ├── login_cubit.dart
│   │       │   └── login_state.dart
│   │       ├── pages/
│   │       │   ├── email_sent_page.dart
│   │       │   ├── forgot_password_page.dart
│   │       │   ├── login_page.dart
│   │       │   ├── otp_page.dart
│   │       │   └── signup_page.dart
│   │       └── widgets/
│   │           ├── custom_pincode.dart
│   │           ├── login_form_widget.dart
│   │           └── resend_otp_after_widget.dart
│   ├── password_vault/
│   │   ├── data/
│   │   │   ├── datasources/
│   │   │   │   └── password_remote_datasource.dart
│   │   │   ├── enum/
│   │   │   │   └── password_streangth.dart
│   │   │   ├── models/
│   │   │   │   ├── password_analysis_model.dart
│   │   │   │   ├── password_analysis_streangth.dart
│   │   │   │   └── password_vault_model.dart
│   │   │   └── repositories/
│   │   │       └── password_repo_impl.dart
│   │   ├── domain/
│   │   │   ├── repositories/
│   │   │   │   └── password_vault_repo.dart
│   │   │   └── usecases/
│   │   │       └── password_vault_usecase.dart
│   │   ├── password_vault_export.dart
│   │   ├── presentation/
│   │   │   ├── cubit/
│   │   │   │   ├── password_vault_cubit.dart
│   │   │   │   └── password_vault_state.dart
│   │   │   ├── pages/
│   │   │   │   ├── analysis_security_page.dart
│   │   │   │   ├── new_password_page.dart
│   │   │   │   ├── passwords_page.dart
│   │   │   │   ├── password_details_page.dart
│   │   │   │   └── search_password_page.dart
│   │   │   └── widgets/
│   │   │       ├── analysis_widgets/
│   │   │       │   ├── analaysis_linear_progress_widget.dart
│   │   │       │   ├── analysis_circular_progress.dart
│   │   │       │   ├── counter_box/
│   │   │       │   │   ├── counter_box.dart
│   │   │       │   │   └── counter_box_row.dart
│   │   │       │   └── password_analysis_widget.dart
│   │   │       ├── new_reocord/
│   │   │       │   ├── new_record_checkboxes_widget.dart
│   │   │       │   ├── new_record_row.dart
│   │   │       │   ├── new_record_text_field.dart
│   │   │       │   ├── password_streangth_analyzer_widget.dart
│   │   │       │   └── password_streangth_check.dart
│   │   │       ├── password_image_widget.dart
│   │   │       ├── password_skeleton_loading_widget.dart
│   │   │       ├── password_skeleton_widget.dart
│   │   │       ├── profile_details/
│   │   │       │   ├── password_details_header_widget.dart
│   │   │       │   └── password_row_details_widget.dart
│   │   │       └── suggestion_textfield.dart
│   │   └── services/
│   │       └── password_analyzer.dart
│   ├── settings/
│   │   ├── presentation/
│   │   │   ├── cubit/
│   │   │   │   ├── settings_cubit.dart
│   │   │   │   └── settings_state.dart
│   │   │   ├── pages/
│   │   │   │   └── settings_page.dart
│   │   │   └── widgets/
│   │   │       ├── section_widget.dart
│   │   │       └── settings_row_widget.dart
│   │   └── settings_export.dart
│   ├── splash/
│   │   ├── presentation/
│   │   │   ├── cubit/
│   │   │   │   ├── splash_cubit.dart
│   │   │   │   └── splash_state.dart
│   │   │   ├── pages/
│   │   │   │   └── splash_page.dart
│   │   │   └── widgets/
│   │   └── splash_export.dart
│   └── users/
│       ├── data/
│       │   ├── datasources/
│       │   │   └── users_remote_datasource.dart
│       │   ├── models/
│       │   │   └── users_model.dart
│       │   └── repositories/
│       │       └── users_repo_impl.dart
│       ├── domain/
│       │   ├── repositories/
│       │   │   └── user_repo.dart
│       │   └── usecases/
│       │       └── users_usecase.dart
│       ├── presentation/
│       │   ├── cubit/
│       │   │   ├── users_cubit.dart
│       │   │   └── users_state.dart
│       │   ├── pages/
│       │   │   ├── edit_profile_page.dart
│       │   │   └── profile_page.dart
│       │   └── widgets/
│       │       ├── profile_image_widget.dart
│       │       └── profile_progress_bar_widget.dart
│       └── users_export.dart
├── firebase_options.dart
├── main_development.dart
├── main_production.dart
├── my_app.dart
└── widgets/
    ├── app_bar/
    │   ├── appbar_subtitle.dart
    │   └── custom_app_bar.dart
    ├── app_text_field.dart
    ├── button_widgets.dart
    ├── custom_image_view.dart
    ├── database_stream_widget.dart
    ├── loader_widget.dart
    ├── show_message/
    │   ├── flutter_toast_widget.dart
    │   ├── show_message_widget.dart
    │   └── snack_bar_widget.dart
    └── widget_export.dart
```
### 🎬 Watch Demo on Google Drive

[![Watch Video](https://img.shields.io/badge/Watch-Video-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1KyH3VHAWIIs6a32l4latGWHLAhBc-2FF/view)


## Packages

![323975159-670cbbd7-ea90-4d08-a22c-d4dc179e568a](https://github.com/user-attachments/assets/b73acf2c-ef03-41d5-83be-ce274e6d0364)


## 📣 Feedback

We value your feedback! Feel free to reach out to us at:
- Mahmoud Alaa: mahmoud3laa2210@gmail.com | [GitHub](https://github.com/MahmoudAlaa22) | [LinkedIn](https://www.linkedin.com/in/mahmoudalaa2210/)
- Waleed Ashraf: eng.waleed.ashraf.farag@gmail.com | [GitHub](https://github.com/waleed750) | [LinkedIn](https://www.linkedin.com/in/waleed-ashrf/)
