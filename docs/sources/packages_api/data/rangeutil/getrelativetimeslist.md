+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "getRelativeTimesList"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## rangeUtil.getRelativeTimesList() function

### rangeUtil.getRelativeTimesList() function

<b>Signature</b>

```typescript
export declare function getRelativeTimesList(timepickerSettings: any, currentDisplay: any): import("lodash").Dictionary<(number | {
    from: string;
    to: string;
    display: string;
    section: number;
} | (() => string) | (() => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | {
    (...items: ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (...items: ({
        from: string;
        to: string;
        display: string;
        section: number;
    } | ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>)[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((separator?: string | undefined) => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((compareFn?: ((a: {
    from: string;
    to: string;
    display: string;
    section: number;
}, b: {
    from: string;
    to: string;
    display: string;
    section: number;
}) => number) | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | {
    (start: number, deleteCount?: number | undefined): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (start: number, deleteCount: number, ...items: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => void, thisArg?: any) => void) | (<U>(callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U, thisArg?: any) => U[]) | {
    <S extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S, thisArg?: any): S[];
    (callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_1>(callbackfn: (previousValue: U_1, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_1, initialValue: U_1): U_1;
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_2>(callbackfn: (previousValue: U_2, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_2, initialValue: U_2): U_2;
} | {
    <S_1 extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(predicate: (this: void, value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S_1, thisArg?: any): S_1 | undefined;
    (predicate: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    } | undefined;
} | ((predicate: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, obj: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => number) | ((value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((target: number, start: number, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => IterableIterator<[number, {
    from: string;
    to: string;
    display: string;
    section: number;
}]>) | (() => IterableIterator<number>) | (() => IterableIterator<{
    from: string;
    to: string;
    display: string;
    section: number;
}>) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => boolean) | (<U_3, This = undefined>(callback: (this: This, value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U_3 | readonly U_3[], thisArg?: This | undefined) => U_3[]) | (<A, D extends number = 1>(this: A, depth?: D | undefined) => {
    done: A;
    recur: A extends readonly (infer InnerArr)[] ? {
        done: InnerArr;
        recur: InnerArr extends readonly (infer InnerArr)[] ? {
            done: InnerArr;
            recur: InnerArr extends readonly (infer InnerArr)[] ? {
                done: InnerArr;
                recur: InnerArr extends readonly (infer InnerArr)[] ? {
                    done: InnerArr;
                    recur: InnerArr extends readonly (infer InnerArr)[] ? {
                        done: InnerArr;
                        recur: InnerArr extends readonly (infer InnerArr)[] ? {
                            done: InnerArr;
                            recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                done: InnerArr;
                                recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                    done: InnerArr;
                                    recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                        done: InnerArr;
                                        recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                            done: InnerArr;
                                            recur: InnerArr extends readonly (infer InnerArr)[] ? any[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                            }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]] extends -1 ? "done" : "recur"] : InnerArr;
            }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]] extends -1 ? "done" : "recur"] : InnerArr;
        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]] extends -1 ? "done" : "recur"] : InnerArr;
    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D] extends -1 ? "done" : "recur"] : A;
}[D extends -1 ? "done" : "recur"][]))[]>;
```
<b>Import</b>

```typescript
import { rangeUtil } from '@grafana/data';
const { getRelativeTimesList } = rangeUtil;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  timepickerSettings | <code>any</code> |  |
|  currentDisplay | <code>any</code> |  |

<b>Returns:</b>

`import("lodash").Dictionary<(number | {
    from: string;
    to: string;
    display: string;
    section: number;
} | (() => string) | (() => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | {
    (...items: ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (...items: ({
        from: string;
        to: string;
        display: string;
        section: number;
    } | ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>)[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((separator?: string | undefined) => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((compareFn?: ((a: {
    from: string;
    to: string;
    display: string;
    section: number;
}, b: {
    from: string;
    to: string;
    display: string;
    section: number;
}) => number) | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | {
    (start: number, deleteCount?: number | undefined): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (start: number, deleteCount: number, ...items: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => void, thisArg?: any) => void) | (<U>(callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U, thisArg?: any) => U[]) | {
    <S extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S, thisArg?: any): S[];
    (callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_1>(callbackfn: (previousValue: U_1, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_1, initialValue: U_1): U_1;
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_2>(callbackfn: (previousValue: U_2, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_2, initialValue: U_2): U_2;
} | {
    <S_1 extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(predicate: (this: void, value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S_1, thisArg?: any): S_1 | undefined;
    (predicate: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    } | undefined;
} | ((predicate: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, obj: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => number) | ((value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((target: number, start: number, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => IterableIterator<[number, {
    from: string;
    to: string;
    display: string;
    section: number;
}]>) | (() => IterableIterator<number>) | (() => IterableIterator<{
    from: string;
    to: string;
    display: string;
    section: number;
}>) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => boolean) | (<U_3, This = undefined>(callback: (this: This, value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U_3 | readonly U_3[], thisArg?: This | undefined) => U_3[]) | (<A, D extends number = 1>(this: A, depth?: D | undefined) => {
    done: A;
    recur: A extends readonly (infer InnerArr)[] ? {
        done: InnerArr;
        recur: InnerArr extends readonly (infer InnerArr)[] ? {
            done: InnerArr;
            recur: InnerArr extends readonly (infer InnerArr)[] ? {
                done: InnerArr;
                recur: InnerArr extends readonly (infer InnerArr)[] ? {
                    done: InnerArr;
                    recur: InnerArr extends readonly (infer InnerArr)[] ? {
                        done: InnerArr;
                        recur: InnerArr extends readonly (infer InnerArr)[] ? {
                            done: InnerArr;
                            recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                done: InnerArr;
                                recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                    done: InnerArr;
                                    recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                        done: InnerArr;
                                        recur: InnerArr extends readonly (infer InnerArr)[] ? {
                                            done: InnerArr;
                                            recur: InnerArr extends readonly (infer InnerArr)[] ? any[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                                }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                            }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]]] extends -1 ? "done" : "recur"] : InnerArr;
                }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]]] extends -1 ? "done" : "recur"] : InnerArr;
            }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]]] extends -1 ? "done" : "recur"] : InnerArr;
        }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D]] extends -1 ? "done" : "recur"] : InnerArr;
    }[[-1, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20][D] extends -1 ? "done" : "recur"] : A;
}[D extends -1 ? "done" : "recur"][]))[]>`

