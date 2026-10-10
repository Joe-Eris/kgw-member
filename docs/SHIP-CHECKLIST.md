# KWGM Ship Checklist

## Required corrections before production
- Replace localhost API URLs in all `config.js` files with the production API URL.
- Set strong database and bootstrap admin credentials.
- Replace Flutterwave test/public/secret keys and test verification.
- Put HTTPS in front of every public endpoint.
- Use object storage/CDN for production video uploads instead of local disk.
- Add YouTube OAuth upload flow before enabling automatic YouTube publishing.
- Configure SMTP/transactional email if email notifications are needed.
- Review member privacy fields and role permissions with church leadership.
- Define retention policy for counselling, child, attendance and financial data.
- Test backups and restore procedures.
- Run security, accessibility, performance and payment UAT.
- Verify all bank account details and USSD flows.
- Add official ministry social URLs.
- Replace placeholder/AI-like copy with approved ministry content.
