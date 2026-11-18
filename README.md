# email-template
Club template for Emails and Newsletters

## Conventions
- Sent emails go in `past-emails/`, named by the date they were created: `YYYY-MM-DD.html`.
- Subject line (the `<title>`): `QTC@URI · [Sub Subject]`.
- **Start new club emails from** `templates/qtc-club-email-template.html` (canonical layout).
- Section cuts: centered `#38BDF8` accent bar (120×4 `bgcolor` cell), not full-width hairlines. Keep the main column white; use `#EAF4FF` only inside inset cards, not as a full section band (it matches the page background and looks broken).

### Section cut (paste between body sections)

```html
<!-- SECTION CUT -->
<tr>
  <td align="center" class="px" style="background:#FFFFFF;padding:8px 40px 20px;text-align:center;">
    <table role="presentation" cellpadding="0" cellspacing="0" border="0" align="center" style="margin:0 auto;">
      <tr>
        <td width="120" height="4" bgcolor="#38BDF8" style="width:120px;height:4px;background-color:#38BDF8;font-size:0;line-height:0;mso-line-height-rule:exactly;border-radius:2px;">&nbsp;</td>
      </tr>
    </table>
  </td>
</tr>
```
