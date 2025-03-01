# Data Dictionary

This **Data Dictionary** provides an overview of the key variables in the **CFPS (2010-2014) dataset**, including their **data types** and **descriptions**.

## **Table: Dataset Variables**

| **Variable Name**      | **Data Type**  | **Description** |
|------------------------|---------------|----------------|
| `region`              | Categorical    | Geographic region where the child resides (e.g., Eastern, Central, Western). |
| `urban_rural`         | Categorical    | Classification of residence as **urban (1) or rural (0)**. |
| `father_absence`      | Categorical    | **1 = Absent, 0 = Present**; whether the child's father is absent from the household. |
| `mother_absence`      | Categorical    | **1 = Absent, 0 = Present**; whether the child's mother is absent from the household. |
| `child_sickness`      | Categorical    | **0 = Healthy, 1 = Occasionally Sick, 2 = Frequently Sick, 3 = Chronically Ill**. |
| `household_income`    | Numeric (Float) | Total annual household income (in RMB). |
| `education_level`     | Categorical    | Highest education level achieved by the child’s primary guardian. |
| `family_size`         | Numeric (Integer) | Number of people living in the household. |
| `access_healthcare`   | Categorical    | **1 = Yes, 0 = No**; whether the child has regular access to healthcare. |
| `parental_education`  | Categorical    | Education level of the child’s parents (e.g., **Primary, Secondary, Higher**). |
| `child_psych_score`   | Numeric (Float) | Child’s psychological well-being score (measured through survey responses). |
| `socioeconomic_index` | Numeric (Float) | Composite index reflecting household’s **economic and social standing**. |
| `migration_status`    | Categorical    | Whether the child or their parents are part of **rural-to-urban migration**. |
| `school_enrollment`   | Categorical    | **1 = Enrolled, 0 = Not Enrolled**; whether the child is currently attending school. |
| `nutrition_access`    | Categorical    | **1 = Adequate, 0 = Inadequate**; whether the child has access to proper nutrition. |
| `mental_health_risk`  | Categorical    | **1 = At Risk, 0 = No Risk**; indicator for potential mental health concerns. |

## **Notes**
- **Categorical variables** are encoded for **machine learning compatibility**.
- **Numeric variables** include both **integer (count-based) and float (index-based) values**.
- The dataset includes **longitudinal tracking from 2010 to 2014**, allowing for **temporal analysis of child well-being**.

For further details on variable transformations and derived features, refer to the **data preprocessing documentation**.
