## Cloud SQL for PostgreSQL: Qwik Start [GSP152]

```

export REGION=


gcloud sql instances create myinstance \
    --database-version=POSTGRES_15 \
    --tier=db-custom-2-7680 \
    --region=$REGION \
    --storage-type=SSD \
    --storage-size=100GB
```

### DONE !!!
