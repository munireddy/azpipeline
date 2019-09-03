# azpipeline
This is Azure pipeline project to deploy a VM.


provisioner "local-exec" {
    command = "az login --service-principal --username \"3d587273-dcac-47f1-b714-72f244c67c52\"  --password \"8ec3a20c-e55e-4341-abec-28d57eab3be1\" --tenant \"59b2865a-7fb8-4ccb-ab68-72cbca88fc48\" && az role assignment create --role \"Virtual Machine Administrator Login\" --assignee \"nineuser@autonomicpro.com\""
}
