# Colomney Lints

Personalized lint rules used by colomney.

This enables additional rules by using [Dart Code Metrics](https://pub.dev/packages/dart_code_metrics) in addition to the standard rules defined in Dart and Flutter.
It helps to make the code more homogeneous.

## Usage

### 1. Install

Add the following code in your `pubspec.yaml`.

```yaml:pubspec.yaml
dev_dependencies:
  colomney_lints:
    git:
      url: git@github.com:shotaIDE/ColomneyFlutterLints.git
      ref: main
```

### 2. Specify the analysis_options.yaml

Add the following code in your `analysis_options.yaml`

```yaml:analysis_options.yaml
include: package:colomney_lints/analysis_options.yaml
```
