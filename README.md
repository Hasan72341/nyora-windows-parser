# nyora-windows-parser

Source repository index for the Nyora desktop reader.

The reader loads its sources from a **signed index** hosted here. Add this link
in the app (Explore → **Add a source repository**):

```
https://hasan72341.github.io/nyora-windows-parser/nyora-repo.json
```

The index (`nyora-repo.json`) is Ed25519-signed; the app verifies the signature
against its embedded public key before loading — an unsigned or altered index is
rejected.
