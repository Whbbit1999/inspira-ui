---
title: File Upload
description: A modern file upload component with a 3D card effect, drag-and-drop functionality, and a responsive grid background pattern.
---

::ComponentLoader{label="Preview" componentName="FileUploadDemo" type="examples"}
::

::alert{type="warning"}
This component uses the `nuxt-only` syntax with the `<ClientOnly>`. If you are not using Nuxt, you can simply remove it.
::

## 使用 CLI 安装

::InstallationCli{componentId="file-upload"}
::

## 手动安装

将以下代码复制并粘贴到同一文件夹中

::code-group

:CodeViewerTab{label="FileUpload.vue" language="vue" componentName="FileUpload" type="ui" id="file-upload"}
:CodeViewerTab{label="FileUploadGrid.vue" language="vue" componentName="FileUploadGrid" type="ui" id="file-upload"}

::

## API

### `FileUpload`

The `FileUpload` component serves as a wrapper for the file upload effect. It manages mouse events to create a 3D perspective.

#### Props

| Prop Name | 类型   | 默认值 | 说明                                                  |
| --------- | ------ | ------ | ----------------------------------------------------- |
| `class`   | String | -      | Additional classes for styling the container element. |

#### Emits

| Event Name | 类型                      | 说明                                                       |
| ---------- | ------------------------- | ---------------------------------------------------------- |
| `onChange` | `(files: File[]) => void` | Callback function triggered when files are added/uploaded. |

#### Usage

```vue [MyComponent.vue]
<FileUpload class="additional-class">
  <!-- Your content here -->
</FileUpload>
```

### `FileUploadGrid`

The `FileUploadGrid` component provides the background grid pattern for the file upload area. It is intended to be used within a `FileUpload` component to create the visual grid effect behind the upload interface.

#### Props

| Prop Name | 类型   | 默认值 | 说明                                   |
| --------- | ------ | ------ | -------------------------------------- |
| `class`   | String | -      | Additional classes for custom styling. |

#### Usage

```vue [MyComponent.vue]
<FileUploadGrid class="custom-class" />
```

## 致谢

- Credits to [kalix127](https://github.com/kalix127) for porting this component.
- Inspired by [AcernityUI](https://ui.aceternity.com/components/file-upload).
