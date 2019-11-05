# Cloud Formation Scripts

List of [Region Ids](https://docs.aws.amazon.com/pt_br/general/latest/gr/rande.html)

### Important topics
* Resources: AWS Resources, mandatory item.
* Parameters: Dynamic inputs.
* Mappings: Static inputs. Commonly used to set environments.
* Outputs: Used to references another stack. E.g: Stack 1 is for VPC, and Stack 2 for EC2 instances. Stack 2 will use Stack 1 references to use the existing VPC..
* Conditions: Can be incorporate into script, very useful to create a resource based on conditions.
* Functions: Most common functions are !Ref, !GetAttr, etc
