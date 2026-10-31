# fastutil.collections Skill

Use this skill to work with Norm module `fastutil.collections` version 4. Use only declarations listed below.

## `fastutil.collections`

Source: `Hash.norm`

### `Hash`

```norm
interface Hash
```

## `fastutil.collections`

Source: `Int2ObjectOpenHashMap.norm`

### `Int2ObjectOpenHashMap`

```norm
class Int2ObjectOpenHashMap<V> extends AbstractInt2ObjectMap<V> implements Serializable, Cloneable, Hash, Int2ObjectMap<V>, Int2ObjectFunction<V>
```

Type parameters:

- `V`

#### `Int2ObjectOpenHashMap`

```norm
Int2ObjectOpenHashMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsKey`

```norm
Boolean containsKey(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `ensureCapacity`

```norm
Void ensureCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `get`

```norm
V? get(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `V?`

#### `getOrDefault`

```norm
V? getOrDefault(Integer arg0, V? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `V?`

Returns: `V?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `put`

```norm
V? put(Integer arg0, V? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `V?`

Returns: `V?`

#### `put`

```norm
V? put(Integer? arg0, V? arg1)
```

Parameters:

- `arg0`: `Integer?`
- `arg1`: `V?`

Returns: `V?`

#### `putIfAbsent`

```norm
V? putIfAbsent(Integer arg0, V? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `V?`

Returns: `V?`

#### `remove`

```norm
V? remove(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `V?`

#### `remove`

```norm
Boolean remove(Integer arg0, Any? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Any?`

Returns: `Boolean`

#### `replace`

```norm
V? replace(Integer arg0, V? arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `V?`

Returns: `V?`

#### `replace`

```norm
Boolean replace(Integer arg0, V? arg1, V? arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `V?`
- `arg2`: `V?`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `trim`

```norm
Boolean trim()
```

Returns: `Boolean`

#### `trim`

```norm
Boolean trim(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

### `int2ObjectOpenHashMapNew`

```norm
Int2ObjectOpenHashMap<V> int2ObjectOpenHashMapNew<V>()
```

Type parameters:

- `V`

Returns: `Int2ObjectOpenHashMap<V>`

### `int2ObjectOpenHashMapNew`

```norm
Int2ObjectOpenHashMap<V> int2ObjectOpenHashMapNew<V>(Integer arg0)
```

Type parameters:

- `V`

Parameters:

- `arg0`: `Integer`

Returns: `Int2ObjectOpenHashMap<V>`

## `fastutil.collections`

Source: `IntArrayList.norm`

### `IntArrayList`

```norm
class IntArrayList extends AbstractIntList implements RandomAccess, Cloneable, Serializable, IntList, IntStack, IntCollection, Collection<Integer>
```

#### `IntArrayList`

```norm
IntArrayList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `add`

```norm
Boolean add(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `add`

```norm
Void add(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Void`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `elements`

```norm
JavaIntArray? elements()
```

Returns: `JavaIntArray?`

#### `ensureCapacity`

```norm
Void ensureCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `getInt`

```norm
Integer getInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `indexOf`

```norm
Integer indexOf(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `lastIndexOf`

```norm
Integer lastIndexOf(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `rem`

```norm
Boolean rem(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `removeInt`

```norm
Integer removeInt(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Integer`

#### `set`

```norm
Integer set(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `Integer`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `size`

```norm
Void size(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `trim`

```norm
Void trim()
```

Returns: `Void`

#### `trim`

```norm
Void trim(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

### `intArrayListNew`

```norm
IntArrayList intArrayListNew()
```

Returns: `IntArrayList`

### `intArrayListNew`

```norm
IntArrayList intArrayListNew(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `IntArrayList`

### `intArrayListOf`

```norm
IntArrayList? intArrayListOf()
```

Returns: `IntArrayList?`

### `intArrayListOf`

```norm
IntArrayList? intArrayListOf(JavaIntArray? arg0)
```

Parameters:

- `arg0`: `JavaIntArray?`

Returns: `IntArrayList?`

### `intArrayListWrap`

```norm
IntArrayList? intArrayListWrap(JavaIntArray? arg0)
```

Parameters:

- `arg0`: `JavaIntArray?`

Returns: `IntArrayList?`

## `fastutil.collections`

Source: `IntOpenHashSet.norm`

### `IntOpenHashSet`

```norm
class IntOpenHashSet extends AbstractIntSet implements Serializable, Cloneable, Hash, IntSet, IntCollection, Collection<Integer>
```

#### `IntOpenHashSet`

```norm
IntOpenHashSet(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `add`

```norm
Boolean add(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `contains`

```norm
Boolean contains(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `ensureCapacity`

```norm
Void ensureCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `remove`

```norm
Boolean remove(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `trim`

```norm
Boolean trim()
```

Returns: `Boolean`

#### `trim`

```norm
Boolean trim(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

### `intOpenHashSetNew`

```norm
IntOpenHashSet intOpenHashSetNew()
```

Returns: `IntOpenHashSet`

### `intOpenHashSetNew`

```norm
IntOpenHashSet intOpenHashSetNew(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `IntOpenHashSet`

### `intOpenHashSetOf`

```norm
IntOpenHashSet? intOpenHashSetOf()
```

Returns: `IntOpenHashSet?`

### `intOpenHashSetOf`

```norm
IntOpenHashSet? intOpenHashSetOf(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `IntOpenHashSet?`

### `intOpenHashSetOf`

```norm
IntOpenHashSet? intOpenHashSetOf(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `IntOpenHashSet?`

### `intOpenHashSetOf`

```norm
IntOpenHashSet? intOpenHashSetOf(Integer arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `IntOpenHashSet?`

### `intOpenHashSetOf`

```norm
IntOpenHashSet? intOpenHashSetOf(JavaIntArray? arg0)
```

Parameters:

- `arg0`: `JavaIntArray?`

Returns: `IntOpenHashSet?`

## `fastutil.collections`

Source: `JavaArrays.norm`

### `JavaIntArray`

```norm
class JavaIntArray
```

#### `JavaIntArray`

```norm
JavaIntArray(JavaIntArrayBindingToken token)
```

Parameters:

- `token`: `JavaIntArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaIntArrayNew`

```norm
JavaIntArray javaIntArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaIntArray`

## `fastutil.collections`

Source: `JavaFunction.norm`

### `JavaFunction`

```norm
interface JavaFunction<K, V> extends JavaFunctionImported1<K, V>
```

Type parameters:

- `K`
- `V`

## `fastutil.collections`

Source: `JavaStack.norm`

### `JavaStack`

```norm
interface JavaStack<K>
```

Type parameters:

- `K`

## `fastutil.collections`

Source: `Long2ObjectOpenHashMap.norm`

### `Long2ObjectOpenHashMap`

```norm
class Long2ObjectOpenHashMap<V> extends AbstractLong2ObjectMap<V> implements Serializable, Cloneable, Hash, Long2ObjectMap<V>, Long2ObjectFunction<V>
```

Type parameters:

- `V`

#### `Long2ObjectOpenHashMap`

```norm
Long2ObjectOpenHashMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsKey`

```norm
Boolean containsKey(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `ensureCapacity`

```norm
Void ensureCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `get`

```norm
V? get(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `V?`

#### `getOrDefault`

```norm
V? getOrDefault(Long arg0, V? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `V?`

Returns: `V?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `put`

```norm
V? put(Long arg0, V? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `V?`

Returns: `V?`

#### `put`

```norm
V? put(Long? arg0, V? arg1)
```

Parameters:

- `arg0`: `Long?`
- `arg1`: `V?`

Returns: `V?`

#### `putIfAbsent`

```norm
V? putIfAbsent(Long arg0, V? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `V?`

Returns: `V?`

#### `remove`

```norm
V? remove(Long arg0)
```

Parameters:

- `arg0`: `Long`

Returns: `V?`

#### `remove`

```norm
Boolean remove(Long arg0, Any? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `Any?`

Returns: `Boolean`

#### `replace`

```norm
V? replace(Long arg0, V? arg1)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `V?`

Returns: `V?`

#### `replace`

```norm
Boolean replace(Long arg0, V? arg1, V? arg2)
```

Parameters:

- `arg0`: `Long`
- `arg1`: `V?`
- `arg2`: `V?`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `trim`

```norm
Boolean trim()
```

Returns: `Boolean`

#### `trim`

```norm
Boolean trim(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

### `long2ObjectOpenHashMapNew`

```norm
Long2ObjectOpenHashMap<V> long2ObjectOpenHashMapNew<V>()
```

Type parameters:

- `V`

Returns: `Long2ObjectOpenHashMap<V>`

### `long2ObjectOpenHashMapNew`

```norm
Long2ObjectOpenHashMap<V> long2ObjectOpenHashMapNew<V>(Integer arg0)
```

Type parameters:

- `V`

Parameters:

- `arg0`: `Integer`

Returns: `Long2ObjectOpenHashMap<V>`

## `fastutil.collections`

Source: `Object2IntOpenHashMap.norm`

### `Object2IntOpenHashMap`

```norm
class Object2IntOpenHashMap<K> extends AbstractObject2IntMap<K> implements Serializable, Cloneable, Hash, Object2IntMap<K>, Object2IntFunction<K>
```

Type parameters:

- `K`

#### `Object2IntOpenHashMap`

```norm
Object2IntOpenHashMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `addTo`

```norm
Integer addTo(K? arg0, Integer arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer`

Returns: `Integer`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `containsKey`

```norm
Boolean containsKey(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

#### `containsValue`

```norm
Boolean containsValue(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

#### `ensureCapacity`

```norm
Void ensureCapacity(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `getInt`

```norm
Integer getInt(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Integer`

#### `getOrDefault`

```norm
Integer getOrDefault(Any? arg0, Integer arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Integer`

Returns: `Integer`

#### `getOrDefault`

```norm
Integer? getOrDefault(Any? arg0, Integer? arg1)
```

Parameters:

- `arg0`: `Any?`
- `arg1`: `Integer?`

Returns: `Integer?`

#### `isEmpty`

```norm
Boolean isEmpty()
```

Returns: `Boolean`

#### `put`

```norm
Integer put(K? arg0, Integer arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer`

Returns: `Integer`

#### `put`

```norm
Integer? put(K? arg0, Integer? arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer?`

Returns: `Integer?`

#### `putIfAbsent`

```norm
Integer putIfAbsent(K? arg0, Integer arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer`

Returns: `Integer`

#### `removeInt`

```norm
Integer removeInt(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Integer`

#### `replace`

```norm
Integer replace(K? arg0, Integer arg1)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer`

Returns: `Integer`

#### `replace`

```norm
Boolean replace(K? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `K?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `Boolean`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `trim`

```norm
Boolean trim()
```

Returns: `Boolean`

#### `trim`

```norm
Boolean trim(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Boolean`

### `object2IntOpenHashMapNew`

```norm
Object2IntOpenHashMap<K> object2IntOpenHashMapNew<K>()
```

Type parameters:

- `K`

Returns: `Object2IntOpenHashMap<K>`

### `object2IntOpenHashMapNew`

```norm
Object2IntOpenHashMap<K> object2IntOpenHashMapNew<K>(Integer arg0)
```

Type parameters:

- `K`

Parameters:

- `arg0`: `Integer`

Returns: `Object2IntOpenHashMap<K>`

## `fastutil.collections.ints`

Source: `ints/AbstractInt2ObjectFunction.norm`

### `AbstractInt2ObjectFunction`

```norm
class AbstractInt2ObjectFunction<V> implements Int2ObjectFunction<V>, Serializable
```

Type parameters:

- `V`

#### `AbstractInt2ObjectFunction`

```norm
AbstractInt2ObjectFunction(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.ints`

Source: `ints/AbstractInt2ObjectMap.norm`

### `AbstractInt2ObjectMap`

```norm
class AbstractInt2ObjectMap<V> extends AbstractInt2ObjectFunction<V> implements Int2ObjectMap<V>, Serializable, Int2ObjectFunction<V>
```

Type parameters:

- `V`

#### `AbstractInt2ObjectMap`

```norm
AbstractInt2ObjectMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.ints`

Source: `ints/AbstractIntCollection.norm`

### `AbstractIntCollection`

```norm
class AbstractIntCollection extends AbstractCollection<Integer> implements IntCollection, Collection<Integer>
```

#### `AbstractIntCollection`

```norm
AbstractIntCollection(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.ints`

Source: `ints/AbstractIntList.norm`

### `AbstractIntList`

```norm
class AbstractIntList extends AbstractIntCollection implements IntList, IntStack, IntCollection, Collection<Integer>
```

#### `AbstractIntList`

```norm
AbstractIntList(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.ints`

Source: `ints/AbstractIntSet.norm`

### `AbstractIntSet`

```norm
class AbstractIntSet extends AbstractIntCollection implements Cloneable, IntSet, IntCollection, Collection<Integer>
```

#### `AbstractIntSet`

```norm
AbstractIntSet(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.ints`

Source: `ints/Int2ObjectFunction.norm`

### `Int2ObjectFunction`

```norm
interface Int2ObjectFunction<V> extends JavaFunction<Integer, V>, IntFunction<V>
```

Type parameters:

- `V`

## `fastutil.collections.ints`

Source: `ints/Int2ObjectMap.norm`

### `Int2ObjectMap`

```norm
interface Int2ObjectMap<V> extends Int2ObjectFunction<V>, JavaMap<Integer, V>
```

Type parameters:

- `V`

## `fastutil.collections.ints`

Source: `ints/IntCollection.norm`

### `IntCollection`

```norm
interface IntCollection extends Collection<Integer>, IntIterable
```

## `fastutil.collections.ints`

Source: `ints/IntIterable.norm`

### `IntIterable`

```norm
interface IntIterable extends Iterable<Integer>
```

## `fastutil.collections.ints`

Source: `ints/IntList.norm`

### `IntList`

```norm
interface IntList extends JavaList<Integer>, Comparable<JavaList<?>>, IntCollection
```

## `fastutil.collections.ints`

Source: `ints/IntSet.norm`

### `IntSet`

```norm
interface IntSet extends IntCollection, JavaSet<Integer>
```

## `fastutil.collections.ints`

Source: `ints/IntStack.norm`

### `IntStack`

```norm
interface IntStack extends JavaStack<Integer>
```

## `fastutil.collections.longs`

Source: `longs/AbstractLong2ObjectFunction.norm`

### `AbstractLong2ObjectFunction`

```norm
class AbstractLong2ObjectFunction<V> implements Long2ObjectFunction<V>, Serializable
```

Type parameters:

- `V`

#### `AbstractLong2ObjectFunction`

```norm
AbstractLong2ObjectFunction(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.longs`

Source: `longs/AbstractLong2ObjectMap.norm`

### `AbstractLong2ObjectMap`

```norm
class AbstractLong2ObjectMap<V> extends AbstractLong2ObjectFunction<V> implements Long2ObjectMap<V>, Serializable, Long2ObjectFunction<V>
```

Type parameters:

- `V`

#### `AbstractLong2ObjectMap`

```norm
AbstractLong2ObjectMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.longs`

Source: `longs/Long2ObjectFunction.norm`

### `Long2ObjectFunction`

```norm
interface Long2ObjectFunction<V> extends JavaFunction<Long, V>, LongFunction<V>
```

Type parameters:

- `V`

## `fastutil.collections.longs`

Source: `longs/Long2ObjectMap.norm`

### `Long2ObjectMap`

```norm
interface Long2ObjectMap<V> extends Long2ObjectFunction<V>, JavaMap<Long, V>
```

Type parameters:

- `V`

## `fastutil.collections.objects`

Source: `objects/AbstractObject2IntFunction.norm`

### `AbstractObject2IntFunction`

```norm
class AbstractObject2IntFunction<K> implements Object2IntFunction<K>, Serializable
```

Type parameters:

- `K`

#### `AbstractObject2IntFunction`

```norm
AbstractObject2IntFunction(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.objects`

Source: `objects/AbstractObject2IntMap.norm`

### `AbstractObject2IntMap`

```norm
class AbstractObject2IntMap<K> extends AbstractObject2IntFunction<K> implements Object2IntMap<K>, Serializable, Object2IntFunction<K>
```

Type parameters:

- `K`

#### `AbstractObject2IntMap`

```norm
AbstractObject2IntMap(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `fastutil.collections.objects`

Source: `objects/Object2IntFunction.norm`

### `Object2IntFunction`

```norm
interface Object2IntFunction<K> extends JavaFunction<K, Integer>, ToIntFunction<K>
```

Type parameters:

- `K`

## `fastutil.collections.objects`

Source: `objects/Object2IntMap.norm`

### `Object2IntMap`

```norm
interface Object2IntMap<K> extends Object2IntFunction<K>, JavaMap<K, Integer>
```

Type parameters:

- `K`

