# Ayush Tiwari

Linux systems engineer. Notes, automation, labs, and audits live in five private repositories. Open the one that matches the work, pull, then push back to the same place.

## Repositories

| | Repository | Use it for | Clone |
| --- | --- | --- | --- |
| 01 | [Infrastructure](https://github.com/Ayushtiwari46/Infrastructure) | Technical notes, commands, SOPs, troubleshooting, and infrastructure knowledge | `gh repo clone Ayushtiwari46/Infrastructure` |
| 02 | [Infrastructure-Automation](https://github.com/Ayushtiwari46/Infrastructure-Automation) | Ansible, shell scripts, Python, PowerShell, and automation projects | `gh repo clone Ayushtiwari46/Infrastructure-Automation` |
| 03 | [Infrastructure-Lab](https://github.com/Ayushtiwari46/Infrastructure-Lab) | OKVM, VMware, Linux labs, experiments, and learning projects | `gh repo clone Ayushtiwari46/Infrastructure-Lab` |
| 04 | [AI-and-Tools](https://github.com/Ayushtiwari46/AI-and-Tools) | AI experiments, prompts, AI-related scripts, and utilities | `gh repo clone Ayushtiwari46/AI-and-Tools` |
| 05 | [Infrastructure-Audit](https://github.com/Ayushtiwari46/Infrastructure-Audit) | Audit checklists, compliance references, security checks, and audit templates | `gh repo clone Ayushtiwari46/Infrastructure-Audit` |

All five are private. This page is only the index.

## Where a new note goes

| Kind of work | Repository | Folder |
| --- | --- | --- |
| Something you learned, a command, or an SOP | Infrastructure | `knowledge-base/` or `platforms/<area>/Notes/` |
| On-call troubleshooting | Infrastructure | `oncall/` |
| A playbook or script you will run again | Infrastructure-Automation | `ansible/`, `shell/`, `python/`, `powershell/`, or `projects/` |
| A lab you are building | Infrastructure-Lab | `okvm/`, `vmware/`, `linux/`, or `experiments/` |
| A prompt or AI experiment | AI-and-Tools | `prompts/` or `experiments/` |
| A checklist or audit run | Infrastructure-Audit | the matching `*-Audit/` folder, or `checklists/` |

Each repository has a `LOG.md`. Add one row when you push work you will want to find later.

## Everyday pull and push

```bash
cd Infrastructure
git pull --rebase
# edit
git add -A
git status
git commit -m "note: short description"
git push
```

Use the same steps in whichever of the five repositories you cloned. Pull first so a second machine does not overwrite the research log.

## Older repositories

The older repositories were merged into the five above and removed. Their full history is in [Legacy-Archive](https://github.com/Ayushtiwari46/Legacy-Archive) under `Retired-Repos/`, with restore steps.

| Older repository | Now lives in |
| --- | --- |
| knowledge-base | Infrastructure `/knowledge-base` |
| Unix, Windows, Network, Storage | Infrastructure `/platforms` |
| Utilities | Infrastructure-Automation `/utilities` |
| Templates-and-Prompts | Split across Infrastructure `/templates`, Infrastructure-Automation `/templates`, and AI-and-Tools `/prompts` |
| Lab, Virtualization | Infrastructure-Lab |
| AI | AI-and-Tools `/experiments/ai` |
| Infra_Audit | Infrastructure-Audit |
| [Legacy-Archive](https://github.com/Ayushtiwari46/Legacy-Archive) | Kept as the historical backup. Useful projects were copied into the five repositories. |
