# Automation Workflows
> Standard workflows for agent automated operations.

## 📝 Daily Log Generation Workflow
```mermaid
graph LR
A[Trigger daily task] --> B[Collect daily operation records]
B --> C[Extract work content, learning notes, problem solving records]
C --> D[Fill in daily log template]
D --> E[Generate draft file in logs/daily/{{date}}.md]
E --> F[Submit commit with message: "draft: daily log {{date}}"]
F --> G[Task completed]
```

## 🔬 Experiment Record Generation Workflow
```mermaid
graph LR
A[Experiment completed] --> B[Collect experimental data, logs, results]
B --> C[Fill in experiment record template]
C --> D[Generate draft file in experiments/{{type}}/{{experiment_name}}.md]
D --> E[Submit commit with message: "draft: experiment record {{experiment_name}}"]
E --> F[Task completed]
```

## 📚 Resource Collection Workflow
```mermaid
graph LR
A[New resource detected] --> B[Extract resource title, URL, author, type]
B --> C[Generate summary and key takeaways]
C --> D[Fill in resource template]
D --> E[Append to corresponding resource list file]
E --> F[Submit commit with message: "draft: add resource {{resource_title}}"]
F --> G[Task completed]
```

## 📊 Weekly Summary Workflow
```mermaid
graph LR
A[Trigger weekly task] --> B[Collect all content from the week]
B --> C[Count work achievements, learning outcomes, experiment results]
C --> D[Fill in weekly summary template]
D --> E[Generate draft file in logs/weekly/{{week}}.md]
E --> F[Submit commit with message: "draft: weekly summary {{week_range}}"]
F --> G[Task completed]
```

## ✅ Content Review Workflow
```mermaid
graph LR
A[Manual review triggered] --> B[Check automatically generated draft content]
B --> C{Content quality OK?}
C -->|Yes| D[Remove draft mark]
C -->|No| E[Modify or delete content]
D --> F[Submit commit with message: "docs: finalize {{content_type}} {{title}}"]
E --> F
F --> G[Review completed]
```
