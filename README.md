# practics

function toCamelCase(str) {
    return str.replace (/-_/g, (match, group1) => group1.toUpperCase());
};

toCamelCase("the-stealth_warrior");
