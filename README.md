# CKYUEIX DSH Plugins

An independent, unofficial static plugin market for DeepSeek Harness.

**Market index:** https://raw.githubusercontent.com/ckyueix/ck-dsh-marketplace/main/index.json

## Available plugin

- **GLM Usage** — `@ckyueix/glm-usage@0.1.0` (DeepSeek Harness `0.2.1-rc.2`).
  Public npm package: https://www.npmjs.com/package/@ckyueix/glm-usage

- **Text Model Vision / 文本模型看图** — `@ckyueix/text-model-vision@0.1.0` (DeepSeek Harness `0.2.1-rc.2`; tested on macOS).
  Native image attachments and text follow-ups for a confirmed text-only model, using explicitly configured visual evidence.
  Public npm package and configuration: https://www.npmjs.com/package/@ckyueix/text-model-vision
  Requires a unique plugin insert and vision-service configuration; image descriptions depend on model capability.

## Add the market to DeepSeek Harness

In Plugins, enable the experimental **Custom plugin markets** feature.
Open Discover, choose **Add index source**, and enter the market index URL above.
Actual plugin installation requires a separate user confirmation.

This repository contains market metadata only, not the plugin's source code.
