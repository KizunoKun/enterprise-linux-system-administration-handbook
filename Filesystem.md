# Filesystem Troubleshooting

Symptoms

- Filesystem full
- Application cannot write data
- Log files growing rapidly

Useful Commands

```bash
df -h

du -sh *

find / -size +500M

journalctl
```

Basic Investigation

1. Check filesystem usage
2. Locate large files
3. Review application logs
4. Clean unnecessary logs
5. Verify free space
