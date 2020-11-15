# Anonymixer Language Files

To add a new Language for the Anonymixer website, it's a simple case of adding in another one of these language files.

Files are structured as key/value pairs, on a line by line basis.
Comments can be made with a `#` character.

```
# English Version (in "messages")
marketing.cloud.title=Beat Blockchain Surveillance

# Thai Version (in "messages.th")
marketing.cloud.title=หลบเลี่ยงการตรวจตราบล็อกเซน
```

If the backtick character is used "`", it needs to be escaped by prefixing it with another backtick character

```
# In (messages.nl), the Phrase "Geen CDN's"

marketing.features.minor.3.title=Geen CDN''s
```
