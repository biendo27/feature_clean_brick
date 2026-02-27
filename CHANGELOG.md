# Changelog

All notable changes to this brick will be documented in this file.

## 1.1.0 - 2026-02-27

- Migrated generated domain usecases from `UseCaseWithParams` to `BaseUseCase<Params, Result>`.
- Updated barrel template state part wiring to be mode-aware (`blocs` for BLoC, `cubits` for Cubit).
- Added hook relocation logic to move generated state files into `presentation/cubits` when `use_bloc = false`.
- Updated README/USAGE with generated conventions for `BaseUseCase` and state file paths.

## 1.0.1 - 2026-02-11

- Updated BrickHub release metadata to use repository `https://github.com/biendo27/feature_clean_brick`.
- Maintained compatibility with `flutter_dcore` projects and existing prompts.

## 1.0.0 - 2026-02-11

- Initial public release on BrickHub.
- Added required `app_package_name` variable to support non-`meup` package imports.
- Added publish metadata (`repository`) and project links in docs.
- Updated docs for BrickHub/Git installation and flutter_dcore audience.
- Added brick-level `LICENSE` and `CHANGELOG`.
