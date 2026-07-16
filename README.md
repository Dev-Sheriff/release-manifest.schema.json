# release-manifest.schema.json
Comprehensive deployment specification for microservices with canary, blue/green, and rollback strategies
**What This Schema Demonstrates**
-Feature Category	Specific Techniques Used
-Core Validation	type, properties, required, additionalProperties, pattern, format
-Number Constraints	minimum, maximum, exclusiveMinimum, exclusiveMaximum
-Array Validation	items, uniqueItems, minItems, maxItems, contains
-String Formats	uuid, email, uri, hostname, date-time, time, uri-reference
-Conditionals	if/then/else (used 6+ times), dependentRequired, dependentSchemas
-Composition	allOf (for additive constraints), $ref for reusability
-Negation	not (to block invalid combinations)
-Data References	$data (to compare two properties dynamically)
-Metadata	title, description, examples, default
-Schema Versioning	Uses Draft 2020-12 ($schema, $id)
-Defensive Design	additionalProperties: false on nested objects to prevent typos
-Real-World Regex	Semantic version, Kubernetes labels, Docker tags, PGP signatures
