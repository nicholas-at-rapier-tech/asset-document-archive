# Tables

## Table :: inspector
> - inspector_id
> - employee_id


## Table :: inspection
> - inspect_id
> - inspectors
> - location_id
> - status (enum :: targeting, inspected, pending, on-progress, in-progress, etc....)
> - inspect_datetime
> - created
> - created_by
> - modified
> - modified_by


## Table :: asset
> - asset_id
> - asset_type
> - location_id
> - documents
> - status (enum :: reusable, empty, renew, rebuild, etc....)
> - remark



## Table :: ms_asset_type
> - code
> - name
> - status
> - created
> - created_by
> - modified
> - modified_by


## Table :: location
> - location_id
> - latitude
> - longitude
> - title
> - description
> - remark
> - created
> - created_by
> - modified
> - modified_by


## Table :: docs
> - doc_id
> - doc_type
> - title
> - mask
> - path
> - extension
> - uploaded
> - uploaded_by
> - created
> - created_by
> - modified
> - modified_by

## Table :: ms_doc_type
> - code
> - name
> - status
> - created
> - created_by
> - modified
> - modified_by


## Table :: archive
> - archive_id
> - doc_id
> - location
> - room
> - cabinet
> - drawer
> - folder
> - archived
> - archived_by
> - taken
> - taken_by
> - modified
> - modified_by



## Table :: archive_quota
> - archive_quota_id
> - location_code
> - room_code
> - cabinet_code
> - drawer_code
> - folder_code
> - status (enum :: empty, fill, booked)
> - modified
> - modified_by