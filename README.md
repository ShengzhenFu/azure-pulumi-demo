# azure-pulumi-demo
```bash
az login
pulumi login
pulumi new typescript
npm install @pulumi/azure-native
az account list-locations -o table
pulumi config set azure-native:location eastasia
pulumi preview
pulumi up
```