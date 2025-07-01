---
title: Safari Mockup
description: An SVG mockup of the Safari browser.
---

::ComponentLoader{label="Preview" componentName="SafariMockupDemo" type="examples" id="mockups"}
::

## 使用 CLI 安装

::InstallationCli{componentId="safari-mockup"}
::

## 手动安装

复制并粘贴以下代码

::CodeViewer{filename="SafariMockup.vue" language="vue" componentName="SafariMockup" type="ui" id="safari-mockup"}
::

## API

| Prop Name | 类型     | 默认值 | 说明                                           |
| --------- | -------- | ------ | ---------------------------------------------- |
| `url`     | `string` | `null` | URL displayed in the mockup's address bar.     |
| `src`     | `string` | `null` | URL of the image to display inside the mockup. |
| `width`   | `number` | `1203` | Width of the mockup SVG in pixels.             |
| `height`  | `number` | `753`  | Height of the mockup SVG in pixels.            |

## Features

- **Realistic Safari Browser Mockup**: Provides an SVG representation of the Safari browser window, ideal for showcasing website designs.
- **Customizable Dimensions**: Adjust the `width` and `height` props to fit your specific needs.
- **Address Bar URL Display**: Use the `url` prop to display a custom URL in the mockup's address bar.
- **Image Display Support**: Use the `src` prop to insert any image into the mockup's content area.
- **Light and Dark Mode Compatibility**: The mockup adapts its colors based on the theme.

## 致谢

- Ported from [Magic UI](https://magicui.design/docs/components/safari).
