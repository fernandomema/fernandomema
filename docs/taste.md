- html/svelte files larger than 600 lines should be refactored/modularized urgently
- rules:
	"rules": {
            "no-unused-vars": "error",
            "no-undef": "error",
            "indent": ["error", 4],

            "no-multiple-empty-lines": ["error", {
                max: 1,
            }],
            "@typescript-eslint/no-unused-vars": "error",
            "@typescript-eslint/no-explicit-any": "warn",
            "@typescript-eslint/no-unused-expressions": "error",
            "prefer-const": "error",
            "brace-style": ["error", "1tbs"],
            "max-depth": ["warn", 4],
            "object-curly-spacing": ["error", "always"],
            "array-bracket-spacing": ["error", "never"],
            "camelcase": ["error", { "properties": "always" }],
            "prefer-template": "warn",
            "spaced-comment": ["error", "always", { "markers": ["/"] }]
        },
