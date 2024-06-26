# NOTY

NOTY is a React Native app that allows users to create folders, add files, manage notes, to-do lists, audio recordings, images, and documents. The app supports light and dark modes and utilizes SQLite for data storage.

## Features

- Create folders with a name, icon, and color.
- Edit folder properties such as color, icon, or name.
- Remove folders.
- Add files with a title, description, and color.
- Edit file properties such as color, title, or description.
- Remove files.
- Notes feature:
  - Add text notes with a title, details, and optional border.
  - Edit or remove text notes.
- To-do list feature:
  - Add, edit, or remove tasks.
  - Check or uncheck tasks as completed.
- Audio feature:
  - Add audio recordings with a title and optional border.
  - Play, pause, resume, and scroll audio recordings.
  - Edit or remove audio recordings.
- Image feature:
  - Add images with a title, description, and optional border.
  - Edit or remove images, including title and description.
- Document feature:
  - Add documents with file extensions such as PPT, PPTX, DOC, DOCX, and PDF.
  - View, edit, or remove documents.
- Dark and light mode:
  - Automatically detects the default mode of the device.
  - Allows users to switch between light and dark modes.
- Search functionality:
  - Search for folders, files, or text within notes.

## Libraries Used

- [react-native-async-storage/async-storage](https://github.com/react-native-async-storage/async-storage) - Asynchronous storage library for React Native.
- [react-navigation/native](https://github.com/react-navigation/react-navigation) - Routing and navigation library for React Native apps.
- [react-navigation/native-stack](https://github.com/react-navigation/react-navigation) - Stack navigator for React Navigation.
- [react-native-document-picker](https://github.com/react-native-document-picker/react-native-document-picker) - Document picker for React Native.
- [react-native-elements](https://github.com/react-native-elements/react-native-elements) - UI component library for React Native.
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) - Icon library for React Native.
- [react-native-track-player](https://github.com/react-native-kit/react-native-track-player) - Audio playback library for React Native.
- [react-native-sqlite-storage](https://github.com/andpor/react-native-sqlite-storage) - SQLite storage library for React Native.
- [react-native-share](https://github.com/react-native-share/react-native-share) - Share API for React Native.
- [react-native-screens](https://github.com/software-mansion/react-native-screens) - Native navigation primitives for React Native.
- [react-native-safe-area-context](https://github.com/th3rdwave/react-native-safe-area-context) - Safe area insets library for React Native.

## Permissions

The app requires the following permission:

- Access to audios, images, and documents to store them in the database.

## Installation

1. Clone the repository.
2. Install the dependencies by running the following command: