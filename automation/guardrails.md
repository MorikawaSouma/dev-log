# Automation Guardrails
> Safety rules that must be followed during all automated operations.

## 🔒 Core Safety Rules
1. **No data forgery**: All content must be true and reflect actual work and learning processes
2. **No reputation forgery**: No automatic follow, star, comment, issue, PR and other operations
3. **No cross-repository operations**: Only modify the content of this repository, no operations on other repositories
4. **No sensitive content**: No submission of any content involving business secrets, personal privacy, or sensitive topics
5. **No destructive operations**: No deletion of existing content without manual confirmation, no modification of manually confirmed content

## 📝 Content Generation Rules
1. **Authenticity**: All content must be based on actual operations and learning, no fictional content
2. **Quality**: Automatically generated content must have practical value, no junk content or placeholder text
3. **Specification**: Content must follow the corresponding template format, maintain uniform style
4. **Mark drafts**: All automatically generated content must be clearly marked as drafts before manual review
5. **Traceability**: Each automatically generated content must have clear source and generation time records

## 📤 Submission Rules
1. **Frequency limit**: No more than 5 commits per day for automated operations
2. **Time limit**: Automated operations are only performed between 9:00-21:00 Beijing time
3. **Commit message specification**:
   - Draft content: `draft: [content type] [title]`
   - Modified content: `docs: [operation] [content type] [title]`
   - Structural adjustment: `chore: [operation] [description]`
4. **Avoid large submissions**: Each commit only contains a single type of content, no mixed submission of multiple unrelated contents

## 🚨 Exception Handling Rules
1. **Task failure**: If an automated task fails, stop immediately, record the error log, and do not retry repeatedly
2. **Content conflict**: If a content conflict is found, stop the operation and wait for manual processing
3. **Rule violation**: If an operation is found to violate the rules, immediately stop all automated tasks and notify the human for review
4. **Data recovery**: If incorrect content is submitted, immediately roll back and record the reason

## 🔍 Regular Audit Rules
1. **Daily audit**: Manually review the automatically generated content of the day every day
2. **Weekly audit**: Conduct a comprehensive review of the repository content every week to clean up invalid content
3. **Rule optimization**: Regularly optimize automation rules and guardrails according to actual operation conditions
4. **Security check**: Regularly check whether there are security risks or rule violations in automated operations
