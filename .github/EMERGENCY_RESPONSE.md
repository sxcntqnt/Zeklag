# Emergency Response - Compromised Keys

## Immediate Actions

1. **Lock the main branch**
   ```bash
   gh api repos/:owner/:repo/branches/main/protection/lock \
     --method PUT \
     -H "Accept: application/vnd.github.v3+json"
