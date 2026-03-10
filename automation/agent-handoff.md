# Agent Handoff Manual
> Operation manual for OpenClaw/agent to take over maintenance of this repository.

## 🎯 Repository Core Objectives
1. **Real contribution**: Generate real, high-quality GitHub contributions through actual work and learning records
2. **Knowledge precipitation**: Accumulate personal technical knowledge, experience, and resources to form a structured knowledge base
3. **Professional image**: Build a professional and reliable personal technical image through long-term stable maintenance
4. **Content value**: The repository content must have practical reference value, not just for brushing contributions

## ✅ Allowed Operations
Tasks that agents can perform automatically:
1. **Daily log generation**: Organize daily work records, learning notes, problem solving processes
2. **Experiment record**: Record experimental processes, results, and conclusions
3. **Resource collection**: Sort and archive high-quality technical resources, articles, and open source projects
4. **Weekly summary**: Generate weekly work and learning summary drafts
5. **Structure maintenance**: Maintain repository directory structure, update index files, and clean up duplicate content
6. **Template optimization**: Improve and optimize various document templates according to usage

## ❌ Prohibited Operations
Tasks that agents are strictly prohibited from performing:
1. Any operation that forges contributions, interactions, or reputations
2. Any operation that modifies other repositories or third-party resources
3. Any operation that deletes or modifies manually confirmed content
4. Any operation that submits sensitive content, private information, or business secrets
5. Any operation that violates GitHub community rules or relevant laws and regulations

## 📅 Update Frequency
1. **Daily tasks**: Run once at 9:00 PM every day to generate daily content
2. **Weekly tasks**: Run once at 8:00 PM every Sunday to generate weekly summaries
3. **Irregular tasks**: Run according to actual needs when new experiments are completed or new resources are collected
4. **Limit**: No more than 5 automated commits per day

## 📄 Output Specifications
1. **Content format**: All content must follow the corresponding template format, maintain uniform style
2. **Draft mark**: All automatically generated content must be marked with "Generated automatically, pending manual review" at the bottom
3. **Commit message**: Follow the unified commit message specification:
   - Draft: `draft: [type] [title]`
   - Modification: `docs: [action] [type] [title]`
   - Chore: `chore: [description]`
4. **Language**: The main content is written in Chinese, technical terms can use English, keep the style professional and concise

## ⚠️ Operation Boundary
1. **Auto-write range**: Only modify files in the following directories:
   - `logs/daily/`
   - `logs/weekly/`
   - `logs/notes/`
   - `experiments/`
   - `resources/`
   - `templates/` (only for template optimization)
2. **Manual confirmation required**:
   - All files in the `docs/` directory
   - Root directory files (README.md, .gitignore, LICENSE)
   - `automation/` directory configuration files
   - Any content involving external evaluation or recommendation

## 🚨 Exception Handling
1. **Task failure**: If a task fails, stop immediately and record the error log in `automation/error.log`
2. **Content conflict**: If a file conflict is found, stop the operation and wait for manual processing
3. **Rule violation**: If an operation is found to violate the rules, immediately stop all automated tasks and notify the human administrator
4. **Rollback mechanism**: If incorrect content is submitted, use `git revert` to roll back immediately and record the reason

## 📞 Contact
If you encounter problems during operation or need to adjust rules, please contact the repository owner for manual processing.
