# strings包函数列表

- [func Contains(s, substr string) bool](Contains.md) 
- [func ContainsAny(s, chars string) bool](ContainsAny.md) 
- [func ContainsRune(s string, r rune) bool](ContainsRune.md) 
- [func Count(s, sep string) int](Count.md) 
- [func EqualFold(s, t string) bool](EqualFold.md) 
- [func Fields(s string) []string](strings/Fields.md) 
- func FieldsFunc(s string, f func(rune) bool) []string 
- func HasPrefix(s, prefix string) bool 
- func HasSuffix(s, suffix string) bool 
- func Index(s, sep string) int 
- func IndexAny(s, chars string) int 
- func IndexFunc(s string, f func(rune) bool) int 
- func IndexRune(s string, r rune) int 
- func Join(a []string, sep string) string 
- func LastIndex(s, sep string) int 
- func LastIndexAny(s, chars string) int 
- func LastIndexFunc(s string, f func(rune) bool) int 
- func Map(mapping func(rune) rune, s string) string 
- func Repeat(s string, count int) string 
- func Replace(s, old, new string, n int) string 
- func Split(s, sep string) []string 
- func SplitAfter(s, sep string) []string 
- func SplitAfterN(s, sep string, n int) []string 
- func SplitN(s, sep string, n int) []string 
- func Title(s string) string 
- func ToLower(s string) string 
- func ToLowerSpecial(_case unicode.SpecialCase, s string) string 
- func ToTitle(s string) string 
- func ToTitleSpecial(_case unicode.SpecialCase, s string) string 
- func ToUpper(s string) string 
- func ToUpperSpecial(_case unicode.SpecialCase, s string) string 
- func Trim(s string, cutset string) string 
- func TrimFunc(s string, f func(rune) bool) string 
- func TrimLeft(s string, cutset string) string 
- func TrimLeftFunc(s string, f func(rune) bool) string 
- func TrimRight(s string, cutset string) string 
- func TrimRightFunc(s string, f func(rune) bool) string 
- func TrimSpace(s string) string
- func NewReader(s string) *Reader 
- func NewReplacer(oldnew ...string) *Replacer 
