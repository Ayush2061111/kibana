<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [SavedObjectsService](./kibana-plugin-server.savedobjectsservice.md) &gt; [importExport](./kibana-plugin-server.savedobjectsservice.importexport.md)

## SavedObjectsService.importExport property

<b>Signature:</b>

```typescript
importExport: {
        objectLimit: number;
        importSavedObjects(options: SavedObjectsImportOptions): Promise<SavedObjectsImportResponse>;
        resolveImportErrors(options: SavedObjectsResolveImportErrorsOptions): Promise<SavedObjectsImportResponse>;
        getSortedObjectsForExport(options: SavedObjectsExportOptions): Promise<Readable>;
    };
```