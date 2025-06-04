---
layout: blog
title: |-
  Here is m**y title in markdown**

  **Look at me I'm so** cool!
date: 2025-06-04T09:17:00.000Z
thumbnail: /images/uploads/2x-819x227_office_hours-header_v2.jpg
rating: 1
props: <table>  <thead>    <tr>      <th>Property</th>      <th>Type</th>    </tr>  </thead>  <tbody>    <tr>      <td><code>type</code></td>      <td>string
  (base, info, success, warning, danger,
  emergency)</td>    </tr>    <tr>      <td><code>heading</code></td>      <td>string</td>    </tr>    <tr>      <td><code>text</code></td>      <td>string
  (no
  HTML)</td>    </tr>    <tr>      <td><code>primaryLabel</code></td>      <td>string</td>    </tr>    <tr>      <td><code>primaryAction</code></td>      <td>URL</td>    </tr>    <tr>      <td><code>secondaryLabel</code></td>      <td>string</td>    </tr>    <tr>      <td><code>secondaryAction</code></td>      <td>URL</td>    </tr>    <tr>      <td><code>duration</code></td>      <td>integer</td>    </tr>  </tbody></table>
---
  - Keep the alert content concise and focused on the message.
  - Use the default icon alert icon, displayed on the left, unless you need to communicate critical information visually such as a pandemic or widespread power outage.
  - Make alerts dismissible unless they contain critical information or an important step users need to take.
  - Limit alerts to one per page; if more than one alert is needed, prefer Base alerts if possible to not overwhelm users.
  - Use Success type to confirm a positive system status to users such as saving a form.
  - Use Danger type to display system status error messages.
  - Only use Emergency type for actual emergencies such as a mission person, weather, or power outage; consider switching the left icon to a relevant icon if one exists.
